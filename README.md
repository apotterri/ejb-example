# ejb-example
Simple EJB app. 

To run the server: `./mvnw clean deploy tomee:run`.

To run the client (in a different shell): `./mvnw compile exec:java -Dexec.mainClass="org.superbiz.remote.App"`

After stopping the server, the AppMap for the process will be in `apache-tomee/tmp/appmap`.


