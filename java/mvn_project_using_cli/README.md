# Creating folder structure using maven

## Pre-requisite
- JDK
- MAVEN

## Steps to create project structure
- Navigate to the directory where project need to be created.
- Open command prompt/terminal at that directory and enter the below command specifying group-id and artifact-id
```
mvn archetype:generate -DgroupId=<group-id> -DartifactId=<artifact-id> -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
```

For more details [refer this](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html) maven documentation
