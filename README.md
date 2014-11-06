

Application can be started with:

    $ mvn clean package
    $ java -jar target/akkaflow-1.0-SNAPSHOT.jar


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
./gradlew build
```

Or use SBT..

Start up the sbt console using `sbt`
Run the Spring boot main program using `runMain mvctest.SampleWebApplication`


And then run JAR as usual, something like this:

Unix
```
nohup java -jar build/libs/spring-boot-scala-web-0.1.0.jar 1>/dev/null 2>&1 &
```
Windows
```
java -jar build/libs/spring-boot-scala-web-0.1.0.jar 1>/dev/null
```

A url listing the hotels is at [http://localhost:8080/hotels](http://localhost:8080/hotels)


# Pending Points

1-Include full supoprt of Akka.

2-Implementation of the Tell Actor Design Pattern.

3-Separation of the View from the MS.
