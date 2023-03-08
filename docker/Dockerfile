
FROM openjdk:8-jre-alpine

COPY echo-0.0.1-SNAPSHOT.jar /echo.war

# Set a non-root user
USER 10014
EXPOSE 8080
ENTRYPOINT java -jar /echo.war
