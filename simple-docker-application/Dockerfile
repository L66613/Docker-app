FROM amazoncorretto:17.0.7
ARG JAR_FILE=target/simple-docker-application-0.0.1-SNAPSHOT.jar
WORKDIR /opt/app
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","app.jar"]