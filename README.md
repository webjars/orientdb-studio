# [WebJar](http://webjars.org) for [orientdb-studio](https://github.com/orientechnologies/orientdb-studio)

Uses production studio build (bundled with [orientdb-community distribution](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22com.orientechnologies%22%20AND%20a%3A%22orientdb-community%22))

NOTE: Usually the same studio version is provided for every minor distribution version (e.g. for 2.0.0-2.0.14), so in most cases it will be ok to use "older" studio.

### Studio version

Change `orient.version` property in pom file with required orient version (e.g. 2.0.12)

### Build

For local (test) build do 

```bash
$mvn clean package
```