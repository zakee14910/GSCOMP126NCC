# Use an ARM64-compatible OpenJDK image
#FROM eclipse-temurin:17-jdk-alpine

# Use an ARM64-compatible OpenJDK image
FROM eclipse-temurin:17-jdk

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file to the container
COPY target/library-system-0.0.1-SNAPSHOT.jar app.jar

# Expose the application port
EXPOSE 8080

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
