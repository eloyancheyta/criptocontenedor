FROM openjdk:17-jdk-slim 

WORKDIR /app
COPY TOTP.jar /app
COPY lib /app/lib


#COPY . . # Copy the current directory . in the project to the workdir . in the image.

CMD ["java", "-jar", "/app/TOTP.jar"]