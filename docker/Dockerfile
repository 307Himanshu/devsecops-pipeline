# Base image with Java 21 Runtime
FROM eclipse-temurin:21-jre

# Working directory inside the container
WORKDIR /app

# Copy the Spring Boot executable JAR
COPY app/target/devops-status-service-0.0.1-SNAPSHOT.jar app.jar

# Application listens on port 8080
EXPOSE 8080

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]