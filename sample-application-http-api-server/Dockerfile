
FROM openjdk:11-jre
ENV HOME_DIR /opt/http-api-server
WORKDIR $HOME_DIR
COPY target/*exec.jar runnable.jar
ENTRYPOINT java -jar runnable.jar
