# Use the official OpenJDK image as a base image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the Maven build output (jar file) to the working directory
COPY target/spring-boot-0.0.1-SNAPSHOT.jar app.jar

# Expose the application on port 8080
EXPOSE 8080

# Command to run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
