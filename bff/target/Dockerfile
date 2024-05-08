FROM amazoncorretto:21.0.2

WORKDIR /app

COPY bff-0.0.1-SNAPSHOT.jar /app/bff.jar
COPY application-docker.properties /app/

CMD ["java", "-jar", "bff.jar"]
