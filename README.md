# kafkainstallation
## Mohan Krishna Alavala
--- 
## Demonstration Skill:
- I'm going to give demonstration on installation and configuration of kafka on windows machine.

## Prerequisites:
- Apache Kafka 2.13
- Zookeeper 3.4
- Java (Java 8 or Java 11)
- IntelliJ IDE
- Powershell

## Introduction to Kafka
- You can instal kafka by clicing on the following [link](https://kafka.apache.org/downloads) 
- After download is completed, you can get a tar file. Extract the tar file by useing command 
1. tar -xzf kafka_2.13-2.7.0.tgz
2. cd kafka_2.13-2.7.0
- After that you need to set the environment variable under KAFKA_HOME with C:\kafka_2.13-2.7.0

## Kafka set up using Maven
- To demonstrate I'm creating a project using maven in IntelliJ IDE.
- You need to sleect the Maven in the left pane and java version on the start screen. Now click on finish
- Next, you need to select the name of the project, which will be the artifact id and click on finish.
- Now, you need to add dependencies to pom.xml file, there are some mandotory dependencies that you need to add.

## Basic commands to use kafka
- To start Kafka environment
---
``bin/zookeeper-server-start.sh config/zookeeper.properties``

``bin/kafka-server-start.sh config/server.properties``

## References
- https://www.tutorialspoint.com/apache_kafka/apache_kafka_installation_steps.htm 
- https://kafka.apache.org/quickstart 
