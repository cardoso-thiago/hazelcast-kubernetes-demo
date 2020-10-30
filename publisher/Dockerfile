FROM adoptopenjdk/openjdk11:jre11u-alpine-nightly
COPY build/libs/publisher*.jar /app.jar

EXPOSE 8080

CMD ["java", "-jar", "/app.jar"]