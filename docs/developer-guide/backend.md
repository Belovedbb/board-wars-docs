---
layout: default
title: Local Backend
parent: Developer Guide
nav_order: 2
---

# Local Backend

The backend is built using Java programming language and uses Maven as it's build system.

After the project is cloned, ensure maven is on your system path, cd to commons module and run 

````sh
    maven clean install
````
then, go back to the base project directory and rerun the command again. 

The project uses mongodb as it's database server, download mongodb and and point it to port 27017 (which is the default port).

Kafka is used by the project as a message broker/logger. It is used to process activity event streams to all services. 

Ensure kafka is on your path, or consult [this](https://adityasridhar.com/posts/how-to-easily-install-kafka-without-zookeeper) wonderful tutorial on how to go about doing that

Finally, we are ready to run the project, enter this command for each of the project in the order below
```sh 
mvn exec:java -Dexec.mainClass=Main -f pom.xml
```
- [x] ConfigurationServiceApplication
- [x] RegistryServiceApplication
- [x] PublicAuthApplication
- [x] PublicGatewayApplication
- [x] V1DelegatorApplication
- [x] KanbanProjectApplication
- [x] ManagementServiceApplication
