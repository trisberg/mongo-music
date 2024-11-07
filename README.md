# Spring Music

This is a sample application for using database services on [Tanzu Platform](https://tanzu.vmware.com/platform) with the [Spring Framework](https://spring.io) and [Spring Boot](https://projects.spring.io/spring-boot/).

This application has been built to store the same domain objects in one of a variety of different persistence technologies - relational database, document store, and key-value store. This sample, when generated by Tanzu Application Accelerator, allows you to choose the one most applicable to the type of data you need to store..

The application use Spring Java configuration and [bean profiles](http://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-profiles.html) to configure the application and the connection objects needed to use the persistence stores.

## Building

This project requires Java version 21 or later to compile.

To build a runnable Spring Boot jar file, run the following command:

```shell
./gradlew clean assemble
```

## Running the application locally

### Starting the database server

Start the MongoDB server using:

```shell
docker run --rm --name mongodb -p 27017:27017 -d mongodb/mongodb-community-server:latest
```

The application can be started locally using the following command:

```shell
java -jar build/libs/mongo-music-1.0.0.jar
```

Access the application by opening your browser using the URL [http://localhost:8080](http://localhost:8080)

## Tanzu Platform deployment

### Prerequisites

1. Access to [Tanzu Platform](https://docs.vmware.com/en/VMware-Tanzu-Platform/index.html) configured for platform builds.
1. The latest Tanzu CLI and plugins from `vmware-tanzu/app-developer` group installed. Installation instructions can be found in the Tanzu Platform documentation: [Before you begin](https://docs.vmware.com/en/VMware-Tanzu-Platform/SaaS/create-manage-apps-tanzu-platform-k8s/getting-started-deploy-app-to-space.html#before-you-begin-0).
1. You have access to a space for your project and you have used `tanzu login` to authenticate and configure your current Tanzu context and set your project and space using `tanzu project use` and `tanzu space use` respectively.

### About the ContainerApp

Change to the root directory of your generated app.

The project contains a `ContainerApp` manifest file that can be used when building and deploying the app. To review the content of this file run:

```sh
cat .tanzu/config/mongo-music.yml
```

### Configure HTTP Ingress Routing

If you want to expose your application with a domain name and route traffic from the domain name to the deployed application, see [Adding HTTP Routing to an Application](https://docs.vmware.com/en/VMware-Tanzu-Platform/SaaS/create-manage-apps-tanzu-platform-k8s/how-to-ingress-to-app.html).

### Build and deploy the app

Change to the root directory of your generated app.

#### Building and deploying the app in one step

You can build and deploy the app with a single command.
Just run:

```sh
tanzu deploy
```

### Create the service and bind it to the app


You can deploy a mongoDB instance using a provided service type.
To list available service types use:

```shell
tanzu services type list
```

Then, create the service instance using:

```shell
tanzu services create MongoDBInstance/music
```

When prompted, bind the service to your deployed app.

You can list the services you have created using:

```shell
tanzu services list
```

#### Scale the number of instances

When the service you created becomes `Ready`, then you can run this command to scale the app to 1 instance:

```shell
tanzu app scale mongo-music --instances=1
```

### Use port-forward to access an app instance

You can use the `app port-forward` command to access your app instance's endpoint.
Just select the instance you want when prompted.
Use the following command to start the port-forward:

```shell
tanzu app port-forward mongo-music --port 8080
```

Then you can access the app using http://localhost:8080.

