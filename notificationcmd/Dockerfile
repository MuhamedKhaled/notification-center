FROM adoptopenjdk/openjdk11:ubi

ARG JAR_FILE=target/*.jar

COPY ${JAR_FILE} app.jar

EXPOSE 8085

ENTRYPOINT ["java","-jar","/app.jar"]