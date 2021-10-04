# cli
Generated with:
````
mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4
````
Just added a mainClass configuration so java -jar works out of the box.

## build
````
mvn package
````

## Run: about 100ms..150ms
````
java -jar target/cli-1.0-SNAPSHOT.jar
````
