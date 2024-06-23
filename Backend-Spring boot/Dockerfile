# Use a base image with JDK for running Spring Boot applications
FROM openjdk:17-jdk-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the packaged JAR file into the container
COPY target/treading-plateform-0.0.1-SNAPSHOT.jar /app/app.jar

# Expose the port that the Spring Boot application uses (default is 8080)
EXPOSE 5454

# Specify the command to run your Spring Boot application when the container starts
CMD ["java", "-jar", "app.jar"]
