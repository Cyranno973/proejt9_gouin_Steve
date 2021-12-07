FROM openjdk:11
ARG JAR_FILE=target/*.jar
COPY rapport-0.0.1-SNAPSHOT.jar mediscreen1.jar
ENTRYPOINT ["java","-jar","/mediscreen1.jar"]