Please follow the below instruction to build and execute the project.

Pre-requisite:
1. Java 8
2. Maven
3. Mongo DB - mongod service instance must be running.
4. Rabbit MQ - MQ server must be started

Compile:
mvn clean install

Run:
mvn spring-boot:run

The sample message is sent via RestController and the message is hardcoded inside the rest controller.
Use the below link and hit the browser to send sample message.
http://localhost:9191

