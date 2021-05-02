FROM adoptopenjdk/openjdk11:jre11u-alpine-nightly
COPY build/libs/consumer*.jar /app.jar

EXPOSE 8081

CMD ["java", "-jar", "/app.jar"]