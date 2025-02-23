FROM openjdk:17-jdk-slim AS build
WORKDIR /app
COPY target/spring-boot-2-rest-service-swagger-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
EXPOSE 9090
