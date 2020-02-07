FROM openjdk:8-jdk-alpine
MAINTAINER mike.castro.b@gmail.com
ADD demo-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]