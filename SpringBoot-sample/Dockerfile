FROM openjdk:8-jdk-alpine
ARG WAR_FILE=target/*.war
COPY ${WAR_FILE} SpringBootApp.war
ENTRYPOINT ["java","-jar","/SpringBootApp.war"]
