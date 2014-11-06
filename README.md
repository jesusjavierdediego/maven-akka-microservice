# Microservice Archetype C

Microservice archetype with Maven, Spring Boot, Akka and Java.
(From: https://github.com/typesafehub/activator-akka-java-spring)

Project contains:
- Easy to test Akka system with a sample actor
- Spray-based RESTful API
- Actor and API sample tests
- View include
- Hibernate based datasource
- Logback-SLF4J logging

# API structure

```
TODO
```

# Build & Run

To build & run:
```
mvn clean package
```

And then run JAR as usual, something like this:

Unix
```
nohup java -jar build/libs/maven-akka-microservice-1.0-SNAPSHOT.jar 1>/dev/null 2>&1 &
```
Windows
```
java -jar build/libs/maven-akka-microservice-1.0-SNAPSHOT.jar 1>/dev/null
```

# Pending Points

1-Include WS Akka support.

2-Implementation of the Tell Actor Design Pattern.
