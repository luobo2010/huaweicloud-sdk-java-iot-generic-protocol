FROM openjdk:8u181-jdk-alpine

RUN mkdir -p /opt/iot/plugin / && chmod -R 777 /opt/

COPY ./target/cae-demo-1.0-SNAPSHOT.jar /opt/iot/plugin

USER root

CMD ["java", "-jar", "/opt/iot/plugin/cae-demo-1.0-SNAPSHOT.jar", "run"]
