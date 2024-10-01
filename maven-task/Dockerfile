# Use an official OpenJDK runtime as a parent image
FROM openjdk:8-jdk-alpine

# Set the working directory in the container
WORKDIR /app

# Copy the compiled application JAR file to the container
COPY target/HelloWorld-1.0-SNAPSHOT.jar /app/HelloWorld.jar

# Command to run the application
CMD ["java", "-jar", "HelloWorld.jar"]