FROM openjdk:8-jdk-alpine
VOLUME /c/Users/eresh.gorantla/
COPY ./target/*.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT exce java -jar app.jar --info
