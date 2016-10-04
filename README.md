# wak-spring-boot
My first Spring boot apps

Create maven project: mvn archetype:generate -DarchetypeArtifactId=maven-archetype-quickstart -DgroupId=wak.rnd -DartifactId=wak-spring-boot -DinteractiveMode=false

Run Spring boot: mvn spring-boot:run

Run Spring boot with defined port: mvn spring-boot:run -Drun.jvmArguments='-Dserver.port=8085'

OR

Add the server port as below on application.properties server.port = 8090 
