# test-mvn-publish

Testing publishing to Maven Central through GitHub

Docs: https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html

## Build the project

```console
$ my-app> mvn package
...
[INFO] --- jar:3.4.2:jar (default-jar) @ my-app ---
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
```

## Run the project

```console
$ my-app> java -cp target/my-app-1.0-SNAPSHOT.jar com.trivikr.app.App
Hello World!
```
