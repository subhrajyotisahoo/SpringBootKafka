FROM eclipse-temurin:21-jdk-alpine
WORKDIR /app
COPY target/stock-service-0.0.1-SNAPSHOT.jar stock-service.jar
EXPOSE 8081
ENTRYPOINT ["/bin/sh", "-c", "sleep 20 && java -jar stock-service.jar"]
#ENTRYPOINT ["java", "-jar", "stock-service.jar"]
