# Base image with Java 21 Runtime
FROM eclipse-temurin:21-jre

# Working directory inside the container
WORKDIR /app

# Copy the JAR file built by Maven
COPY app/target/devops-status-service-1.0.0.jar app.jar

# Application listens on port 8080
EXPOSE 8080

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]