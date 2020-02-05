
FROM openjdk:11-jre
ENV HOME_DIR /opt/db-changelog-job
WORKDIR $HOME_DIR
COPY target/*exec.jar runnable.jar
ENTRYPOINT java -jar runnable.jar
