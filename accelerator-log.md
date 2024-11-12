# Accelerator Log

## Options
```json
{
  "databaseType" : "h2",
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
┃ ┃ Debug deploy/tpfork8s/tanzu.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/tpfork8s/.tanzu/config/spring-music.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/tpfork8s/.tanzu/config/spring-music-mysql-instance.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/tpfork8s/.tanzu/config/spring-music-mongodb-instance.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/tpfork8s/.tanzu/config/spring-music-binding.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/tpfork8s/.tanzu/config/spring-music-redis-instance.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/tpfork8s/.tanzu/config/spring-music-postgresql-instance.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug accelerator.yaml matched [accelerator.yaml, accelerator.axl] -> excluded
┃ ┃ Debug README.md didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug build.gradle didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gitattributes didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug gradle.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug settings.gradle didn't match [accelerator.yaml, accelerator.axl] -> included
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
┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[1].otherwise (IfElse)
┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[1].otherwise.then (Chain)
┃ ┃ ┃ ┃  Info Running Chain(ApplyTo, ApplyTo, IfElse, IfElse, IfElse, IfElse, IfElse, Select)
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[0].apply (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceSnippet, RewritePath)
┃ ┃ ┃ ┃ ┃ ╺  Info Will replace [spring-music->mongo-music]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[0].apply.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'deploy/tpfork8s/tanzu.yml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yml, folder=deploy/tpfork8s/, filename=tanzu.yml, g0=deploy/tpfork8s/tanzu.yml, g1=deploy/tpfork8s/, g2=tanzu.yml, g3=tanzu.yml, g4=.yml} and was rewritten to 'tanzu.yml'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[1].apply (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[1].apply.transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [spring-music->mongo-music]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[1].apply.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'deploy/tpfork8s/.tanzu/config/spring-music.yml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yml, folder=deploy/tpfork8s/.tanzu/config/, filename=spring-music.yml, g0=deploy/tpfork8s/.tanzu/config/spring-music.yml, g1=deploy/tpfork8s/.tanzu/config/, g2=spring-music.yml, g3=spring-music.yml, g4=.yml} and was rewritten to '.tanzu/config/mongo-music.yml'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[2] (IfElse)
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[2].then (Let)
┃ ┃ ┃ ┃ ┃ Debug Adding symbol id with value '1ef3c9'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[2].then.in.apply (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, OpenRewriteRecipe, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[2].then.in.apply.transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [spring-music->mongo-music]
┃ ┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[2].then.in.apply.transformations[1] (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[2].then.in.apply.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug Path 'deploy/tpfork8s/.tanzu/config/spring-music-binding.yml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yml, folder=deploy/tpfork8s/.tanzu/config/, filename=spring-music-binding.yml, g0=deploy/tpfork8s/.tanzu/config/spring-music-binding.yml, g1=deploy/tpfork8s/.tanzu/config/, g2=spring-music-binding.yml, g3=spring-music-binding.yml, g4=.yml} and was rewritten to '.tanzu/config/mongo-music-binding.yml'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[3] (IfElse)
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[4] (IfElse)
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[5] (IfElse)
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[5].then.apply (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[5].then.apply.transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [spring-music->mongo-music]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[5].then.apply.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'deploy/tpfork8s/.tanzu/config/spring-music-mongodb-instance.yml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yml, folder=deploy/tpfork8s/.tanzu/config/, filename=spring-music-mongodb-instance.yml, g0=deploy/tpfork8s/.tanzu/config/spring-music-mongodb-instance.yml, g1=deploy/tpfork8s/.tanzu/config/, g2=spring-music-mongodb-instance.yml, g3=spring-music-mongodb-instance.yml, g4=.yml} and was rewritten to '.tanzu/config/mongo-music-mongodb-instance.yml'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.then.transformations[6] (IfElse)
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ Debug LICENSE matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug .gitattributes matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug gradle.properties matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/albums.json matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug deploy/tpfork8s/.tanzu/config/spring-music-mysql-instance.yml didn't match [!'deploy/**'] -> excluded
┃ ┃ ┃ ┃ ┃ Debug deploy/tpfork8s/.tanzu/config/spring-music-redis-instance.yml didn't match [!'deploy/**'] -> excluded
┃ ┃ ┃ ┃ ┃ Debug deploy/tpfork8s/.tanzu/config/spring-music-postgresql-instance.yml didn't match [!'deploy/**'] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug build.gradle matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/config/data/RedisConfig.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/redis/RedisAlbumRepository.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/jpa/JpaAlbumRepository.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/RandomIdGenerator.java matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug tanzu.yml matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music.yml matched [!'deploy/**'] -> included
┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music-binding.yml matched [!'deploy/**'] -> included
┃ ┃ ┃ ┗ ┗ Debug .tanzu/config/mongo-music-mongodb-instance.yml matched [!'deploy/**'] -> included
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[2] (IfElse)
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[3] (IfElse)
┃ ┃ ┃ ┃ Debug LICENSE matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gitignore matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gitattributes matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug gradle.properties matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug settings.gradle matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/albums.json matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug README.md matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug build.gradle matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/config/data/RedisConfig.java didn't match [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/redis/RedisAlbumRepository.java didn't match [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/jpa/JpaAlbumRepository.java didn't match [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/RandomIdGenerator.java didn't match [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> excluded
┃ ┃ ┃ ┃ Debug tanzu.yml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music.yml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music-binding.yml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┗ Debug .tanzu/config/mongo-music-mongodb-instance.yml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/domain/RandomIdGenerator.java' && !'src/main/java/com/example/music/repositories/jpa/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4] (IfElse)
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ╺  Info Will replace [spring-music->mongo-music]
┃ ┃ ┃ ╺  Info Will replace [JAVA_VERSION->21]
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7] (Let)
┃ ┃ ┃ ┃ Debug Adding symbol uuid with value '88634b2f-091a-4484-be4f-0fabb90c772e'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ApplyTo, Merge, UniquePath, Merge, UniquePath, Provenance)
┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[7].in.transformations[0].apply (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Select, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ Debug LICENSE matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitattributes matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/albums.json matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music-binding.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music-mongodb-instance.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug tanzu.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ApplyTo, ApplyTo, ApplyTo, ApplyTo, ApplyTo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[0].apply (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[1].apply (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '<java.version>.*<' with '<java.version>21<'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[2].apply (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex 'sourceCompatibility = .*' with 'sourceCompatibility ...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[3].apply (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '(?<unmodified>JavaVersion\.VERSION_)(\d+)' with '${unmodified}21'
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ ╺ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[4].apply (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[2] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.tanzu/config/mongo-music-binding.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/domain/Album.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/header.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitignore', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/web/AlbumController.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitattributes', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/grid.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/albums.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/info.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/footer.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/status.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/app.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build.gradle', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/errors.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/web/InfoController.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/domain/ApplicationInfo.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/example/music/ApplicationTests.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/img/glyphicons-halflings-white.png', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'LICENSE', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'settings.gradle', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/albums.json', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/errors.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.tanzu/config/mongo-music.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/albumForm.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/css/app.css', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/Application.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/list.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradle.properties', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/index.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/img/glyphicons-halflings.png', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/status.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/albums.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/web/ErrorController.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.tanzu/config/mongo-music-mongodb-instance.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/css/multi-columns-row.css', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'tanzu.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┗ Debug Multiple representations for path 'src/main/resources/application.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[3] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Select, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ Debug .tanzu/config/mongo-music-binding.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitattributes matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/albums.json matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music-mongodb-instance.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tanzu.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/resources/application.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[3].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[3].sources[1].validated (IfElse)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[7].in.transformations[3].sources[1].validated.then (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [gradlew*, gradle/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music-binding.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitattributes didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/albums.json didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/mongo-music-mongodb-instance.yml didn't match [gradlew*, gradle/**] -> excluded
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
