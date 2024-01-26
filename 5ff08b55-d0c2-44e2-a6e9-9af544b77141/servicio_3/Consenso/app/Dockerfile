FROM openjdk:17-jdk-slim 

WORKDIR /app
COPY Consenso.jar /app
COPY lib /app/lib

#COPY *.java /app/
#RUN javac *.java
#COPY . . # Copy the current directory . in the project to the workdir . in the image.

#CMD ["java", "Servidor"]
CMD ["java", "-jar", "/app/Consenso.jar"]