FROM openjdk:11-jre-slim
VOLUME /tmp
COPY target/java-docker-app.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]