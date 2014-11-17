To install the archetype :
```mvn install``` here

To test the archetype, in a new folder :

```
mvn archetype:generate -DinteractiveMode=false   -DarchetypeGroupId=demo -DarchetypeArtifactId=archetype -DarchetypeVersion=1.0-SNAPSHOT   -DenableHealthcheck=false -DgroupId=test -Dversion=1.0.0 -DartifactId=test 
```
