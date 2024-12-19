FROM openjdk:17-jdk-slim
EXPOSE 8080
COPY target/empty-spring-proj.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
