FROM openjdk:17-jdk-slim 

WORKDIR /app
COPY GestorMapaServicio.jar /app
COPY lib /app/lib


#COPY . . # Copy the current directory . in the project to the workdir . in the image.

CMD ["java", "-jar", "/app/GestorMapaServicio.jar"]