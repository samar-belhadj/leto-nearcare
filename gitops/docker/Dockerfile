FROM openjdk:11-jdk-slim
WORKDIR /config-server
ADD /target/config-server-1.0.2.jar config-server-1.0.2.jar
EXPOSE 2003
ENTRYPOINT [ "java", "-jar", "config-server-1.0.2.jar" ]