FROM openjdk:21

COPY target/consumer1-0.0.1-SNAPSHOT.jar /app/app.jar

WORKDIR /app

EXPOSE 8082

CMD ["java", "-jar", "app.jar"]