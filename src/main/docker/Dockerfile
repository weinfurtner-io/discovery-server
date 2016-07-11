FROM frolvlad/alpine-oraclejdk8:slim
MAINTAINER jared@weinfurtner.io
ADD discovery-server-0.0.1-SNAPSHOT.jar discovery-server.jar
RUN sh -c 'touch /discovery-server.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/discovery-server.jar"]