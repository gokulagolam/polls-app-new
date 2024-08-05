# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file to the container
COPY target/polls-0.0.1-SNAPSHOT.jar /app/polls.jar

# Expose port 8081
EXPOSE 8081

# Run the JAR file
ENTRYPOINT ["java", "-jar", "/app/polls.jar"]
