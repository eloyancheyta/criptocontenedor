FROM openjdk:17-jdk-slim 

WORKDIR /app
COPY LEA.jar /app
COPY lib /app/lib 

# COPY . .

CMD ["java", "-jar", "/app/LEA.jar"]