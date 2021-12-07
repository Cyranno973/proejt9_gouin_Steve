FROM openjdk:11
ARG JAR_FILE=target/*.jar
COPY mediscreen-0.0.1-SNAPSHOT.jar mediscreen.jar
ENTRYPOINT ["java","-jar","/mediscreen.jar"]