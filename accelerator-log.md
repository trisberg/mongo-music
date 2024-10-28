# Accelerator Log

## Options
```json
{
  "deploymentType" : "tpfork8s",
  "persistenceType" : "mongodb",
  "includeBuildToolWrapper" : true,
  "javaVersion" : "21",
  "projectName" : "mongo-music"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Exclude, GeneratorValidationTransform, UniquePath)
┃ ┏ engine.transformations[0] (Exclude)
┃ ┃  Info Will exclude [accelerator.yaml, accelerator.axl]
┃ ┃ Debug accelerator.axl matched [accelerator.yaml, accelerator.axl] -> excluded
┃ ┃ Debug LICENSE didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/cloudfoundry/manifest.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/cloudfoundry/project.toml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/kubernetes/deployment.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/kubernetes/service.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/tpfork8s/tanzu.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/tpfork8s/.tanzu/config/spring-music.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug accelerator.yaml matched [accelerator.yaml, accelerator.axl] -> excluded
┃ ┃ Debug README.md didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug build.gradle didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gitattributes didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug gradle.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug settings.gradle didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .idea/gradle.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .idea/.gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .idea/workspace.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .idea/misc.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/albums.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/index.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/css/app.css didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/js/info.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/js/errors.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/js/status.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/js/albums.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/js/app.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/status.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/list.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/grid.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/albums.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/errors.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/footer.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/header.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/albumForm.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/application.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/Application.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/config/data/RedisConfig.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/repositories/redis/RedisAlbumRepository.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/repositories/jpa/JpaAlbumRepository.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/domain/Album.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┗ Debug src/main/java/com/example/music/domain/RandomIdGenerator.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┏ ┏ engine.transformations[1].validated (Chain)
┃ ┃ ┃  Info Running Chain(ApplyTo, IfElse, IfElse, IfElse, IfElse, ApplyTo, ApplyTo, Let)
┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[0].apply (TextPreprocessor)
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1] (IfElse)
┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[1].otherwise (Chain)
┃ ┃ ┃ ┃  Info Running Chain(IfElse, UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0] (IfElse)
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ApplyTo, ApplyTo)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then.transformations[0].apply (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then.transformations[0].apply.transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [spring-music->mongo-music]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then.transformations[0].apply.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'deploy/tpfork8s/tanzu.yml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yml, folder=deploy/tpfork8s/, filename=tanzu.yml, g0=deploy/tpfork8s/tanzu.yml, g1=deploy/tpfork8s/, g2=tanzu.yml, g3=tanzu.yml, g4=.yml} and was rewritten to 'tanzu.yml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then.transformations[1].apply (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then.transformations[1].apply.transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [spring-music->mongo-music]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then.transformations[1].apply.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug Path 'deploy/tpfork8s/.tanzu/config/spring-music.yml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yml, folder=deploy/tpfork8s/.tanzu/config/, filename=spring-music.yml, g0=deploy/tpfork8s/.tanzu/config/spring-music.yml, g1=deploy/tpfork8s/.tanzu/config/, g2=spring-music.yml, g3=spring-music.yml, g4=.yml} and was rewritten to '.tanzu/config/mongo-music.yml'
┃ ┃ ┃ ┗ ╺ engine.transformations[1].validated.transformations[1].otherwise.transformations[1] (UniquePath)
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[2] (IfElse)
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[3] (IfElse)
┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[3].then (Exclude)
┃ ┃ ┃ ┃  Info Will exclude [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**]
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug .gitattributes didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/jpa/JpaAlbumRepository.java matched [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> excluded
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug LICENSE didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music.yml didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug deploy/kubernetes/service.yaml didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug README.md didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/config/data/RedisConfig.java matched [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/RandomIdGenerator.java matched [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> excluded
┃ ┃ ┃ ┃ Debug .gitignore didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/project.toml didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/redis/RedisAlbumRepository.java matched [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> excluded
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug build.gradle didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug deploy/kubernetes/deployment.yaml didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug settings.gradle didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/albums.json didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/manifest.yml didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug gradle.properties didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┃ Debug tanzu.yml didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┗ Debug src/main/resources/application.yml didn't match [src/main/java/com/example/music/config/data/**, src/main/java/com/example/music/domain/RandomIdGenerator.java, src/main/java/com/example/music/repositories/jpa/**, src/main/java/com/example/music/repositories/redis/**] -> included
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4] (IfElse)
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[5].apply (ReplaceText)
┃ ┃ ┃ ┗  Info Will replace [spring-music->mongo-music]
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[6].apply (ReplaceText)
┃ ┃ ┃ ┗  Info Will replace [JAVA_VERSION->21]
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7] (Let)
┃ ┃ ┃ ┃ Debug Adding symbol uuid with value '30096025-993d-432e-b177-704d398dd21d'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ApplyTo, Merge, UniquePath, Merge, UniquePath, Provenance)
┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[7].in.transformations[0].apply (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Include, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitattributes matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/service.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/project.toml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/deployment.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/albums.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/manifest.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug tanzu.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ApplyTo, ApplyTo, ApplyTo, ApplyTo, ApplyTo, ApplyTo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[0].apply (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[1].apply (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '<java.version>.*<' with '<java.version>21<'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[2].apply (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex 'sourceCompatibility = .*' with 'sourceCompatibility ...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[3].apply (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '(?<unmodified>JavaVersion\.VERSION_)(\d+)' with '${unmodified}21'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[4].apply (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[5].apply (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ ┗  Info Will replace regex 'jre: \{ version: \d*\.\+' with 'jre: \{ version: 21....(truncated)'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[2] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/domain/Album.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitignore', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/header.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/web/AlbumController.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'deploy/cloudfoundry/project.toml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitattributes', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/albums.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/grid.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/info.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/misc.xml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/footer.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/status.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/workspace.xml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/app.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build.gradle', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/gradle.xml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/errors.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/web/InfoController.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/img/glyphicons-halflings-white.png', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'deploy/kubernetes/deployment.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'LICENSE', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/example/music/ApplicationTests.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/domain/ApplicationInfo.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'settings.gradle', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/albums.json', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/errors.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/css/app.css', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/albumForm.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.tanzu/config/mongo-music.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'deploy/cloudfoundry/manifest.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/list.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/Application.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/.gitignore', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'deploy/kubernetes/service.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradle.properties', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/index.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/img/glyphicons-halflings.png', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/status.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/albums.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/web/ErrorController.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/css/multi-columns-row.css', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'tanzu.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┗ Debug Multiple representations for path 'src/main/resources/application.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[3] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Include, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[3].sources[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/project.toml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitattributes matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/deployment.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/albums.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/manifest.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/service.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tanzu.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[3].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[3].sources[1].validated (IfElse)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[7].in.transformations[3].sources[1].validated.then (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [gradlew*, gradle/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/project.toml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitattributes didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/deployment.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/albums.json didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/manifest.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/service.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tanzu.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug gradlew.bat matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[7].in.transformations[4] (UniquePath)
┃ ┗ ┗ ┗ ┗ ╺ engine.transformations[1].validated.transformations[7].in.transformations[5] (Provenance)
┗ ╺ engine.transformations[2] (UniquePath)
```
