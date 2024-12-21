# Use a lightweight base image
FROM amazoncorretto:17

# Set the working directory
WORKDIR /app

# Copy the application JAR to the container
COPY target/HelloController-0.0.1-SNAPSHOT.jar app.jar

# Expose the port your app runs on (e.g., 8080)
EXPOSE 8080

# Command to run your application
ENTRYPOINT ["java", "-jar", "app.jar"]