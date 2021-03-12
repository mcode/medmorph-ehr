# Process Message Operation Helper

This project is a library to add the $process-message operation to HAPI-based FHIR servers.
Due to the many different ways HAPI servers can be setup, there is some configuration required.


# Installation

This project can be added to an existing Maven-based project, add this dependency to `pom.xml`:

```xml
<dependency>
  <groupId>org.mitre.hapifhir</groupId>
  <artifactId>process-message-operation</artifactId>
  <version>0.0.1</version>
</dependency>
```

Or for a Gradle-based project, add this to `build.gradle`:

```
compile 'org.mitre.hapifhir:process-message-operation:0.0.1'

```


 TODO: steps on how to use it



# Development

To install the current working version to your local Maven repo, run
```
./gradlew publishToMavenLocal
```