This project is a "hello world" demo for micro-service built by "spring boot".

-------------------------------------------------------------------
h1. Precondition:
Install JDK1.8, and set environment variable: JAVA_HOME
Install Maven3 (3.5.0), and set environment variable: MAVEN_HOME

-------------------------------------------------------------------
h1. How to import the project into Eclipse
a. Generate the Eclipse project files:
    > cd demo-springboot-helloworld
    > mvn eclipse:eclipse
b. Then open your Eclipse to import the project.

-------------------------------------------------------------------
1. Start Eureka Server
How to build:
> cd demo-springboot-helloworld
> mvn clean package

How to Startup:
> cd demo-springboot-helloworld\target\
> java -jar demo-springboot-helloworld-1.0-SNAPSHOT.jar

URL Links:
#Visit the micro-service link:
    http://localhost:8080/