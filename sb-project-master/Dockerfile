FROM openjdk:8-jdk-alpine

COPY target/gs-rest-service-0.2.0.jar  app.jar

EXPOSE 8080
ENTRYPOINT ["java","-jar","/app.jar"]
