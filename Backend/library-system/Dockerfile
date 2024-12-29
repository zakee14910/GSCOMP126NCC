# Use a multi-architecture base image
FROM openjdk:17-jdk-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file to the container
COPY target/library-system-0.0.1-SNAPSHOT.jar app.jar

# Expose the application's port
EXPOSE 8080

# Command to run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
