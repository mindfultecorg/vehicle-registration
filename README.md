# Vehicle Registration

Exercises used for training

## Prerequisites

Set up a working environment
- An IDE of your choice (VS Code, IDEA, Eclipse, vim)
- [JDK 17](https://adoptium.net/temurin/releases/?version=17)
- [Maven 3.8](https://maven.apache.org/download.cgi)

## Create a Maven-based project

Create a simple Maven-based project with [archetype](https://maven.apache.org/guides/introduction/introduction-to-archetypes.html) `maven-archetype-simple`

```bash
$> mvn archetype:generate \
-DgroupId=org.mindfultec.training \
-DartifactId=vehicle-registration \
-DarchetypeArtifactId=maven-archetype-simple \
-DarchetypeVersion=1.4 -DinteractiveMode=false
```

Run

```bash
$> mvn test
$> mvn package
$> java -cp target/vehicle-registration-1.0-SNAPSHOT.jar org.mindfultec.training.App
```