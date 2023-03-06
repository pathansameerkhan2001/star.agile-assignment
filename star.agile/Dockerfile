FROM openjdk:11
EXPOSE 8080
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} star.agile-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/star.agile-0.0.1-SNAPSHOT.jar"]
