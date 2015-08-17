# Maven archetype for Java EE 7 microservices-based application

## How to use

First of all you need install this archetype into your local maven repository.
Clone the project from gihub and run ```mvn install```

Now you are ready to use it. 

```
	  mvn archetype:generate \
	  -DarchetypeGroupId=com.agritsik.maven.archetypes \
	  -DarchetypeArtifactId=javaee7-micro \
	  -DarchetypeVersion=1.0-beta-1
# OR
	  mvn archetype:generate \
	  -DarchetypeGroupId=com.agritsik.maven.archetypes \
	  -DarchetypeArtifactId=javaee7-micro \
	  -DarchetypeVersion=1.0-beta-1 \
	  -DgroupId=com.agritsik.samples \
	  -DartifactId=test-new-archetype
```
