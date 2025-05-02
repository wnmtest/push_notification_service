# Use Java 17 base image
FROM openjdk:17

EXPOSE 9892

# Copy the JAR file from host to container
ADD NotificationService-0.0.1-SNAPSHOT.jar NotificationService-0.0.1-SNAPSHOT.jar

# Command to run the app
ENTRYPOINT ["java", "-jar", "NotificationService-0.0.1-SNAPSHOT.jar"]
