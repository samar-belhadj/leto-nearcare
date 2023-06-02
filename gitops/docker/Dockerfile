FROM openjdk:11-jdk-slim

WORKDIR /config-server

RUN apt-get update && apt-get -y install curl

ADD target/config-server-1.0.15.jar config-server-1.0.15.jar

EXPOSE 2003

ENTRYPOINT [ "java", "-jar", "config-server-1.0.15.jar" ]
