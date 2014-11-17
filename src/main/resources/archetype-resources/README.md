Your project ${groupId}:${artifactId} has been generated.

To run it :
-----------

```mvn clean jboss-as:run```
or use the Eclipse Run [$artifactId] jboss run.launch

to access the web application, browse ```http://localhost:8080/$artifactId```


#if ( $enableHealthcheck == "true" ) 
And healthcheck is deployed at ```http://localhost:8080/${artifactId}/healthcheck```
#end

