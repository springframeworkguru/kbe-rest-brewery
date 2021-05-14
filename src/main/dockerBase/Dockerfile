FROM openjdk:11-jre-slim

ENV JAVA_OPTS " -Xms512m -Xmx512m -Djava.security.egd=file:/dev/./urandom"

WORKDIR application

COPY ../../../target/kbe-rest-brewery-0.0.1-SNAPSHOT.jar ./

ENTRYPOINT ["java", "-jar", "kbe-rest-brewery-0.0.1-SNAPSHOT.jar"]