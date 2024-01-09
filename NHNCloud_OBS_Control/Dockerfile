FROM openjdk:17-alpine
ARG WAR_FILE=/NHNCloud_OBS_Control/target/*.war
COPY ${WAR_FILE} app.war
ENTRYPOINT ["java","-jar","/app.war"]
