FROM adoptopenjdk/openjdk11:alpine-jre
ARG JAR_FILE=target/*.jar 
COPY demo-0.0.1-SNAPSHOT.jar note-database.jar  
ENTRYPOINT ["java","-jar","/note-database.jar"]
# ENTRYPOINT ["java","-Dspring.data.mongodb.uri=mongodb://mongodb:27017/mediscreen","/note-database.jar"]