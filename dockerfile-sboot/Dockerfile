FROM openjdk:8-jre-alpine

MAINTAINER rajesh@unigps.in

COPY target/app.jar app.jar

ENTRYPOINT ["/usr/bin/java", "-Djava.security.egd=file:/dev/./urandom", "-Djasypt.encryptor.password=secret",  "-jar","app.jar"]
