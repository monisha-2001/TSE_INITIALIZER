# Use the official OpenJDK base image with the desired Java version
FROM openjdk:11

# Set the working directory inside the container
WORKDIR /app

# Copy the compiled Java application JAR file to the container
COPY C:\Users\e013229\Desktop\tse\tseinit-master\target\*.jar Jpademo-0.0.1-SNAPSHOT.jar

# Expose the port your application will run on (change this if needed)
EXPOSE 8080

# Command to run the Java application
CMD ["java", "-jar", "app.jar"]