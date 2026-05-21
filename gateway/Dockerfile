FROM eclipse-temurin:21-jdk

WORKDIR /app

COPY target/*SNAPSHOT.jar api-gateway.jar

ENTRYPOINT ["java","-jar","api-gateway.jar"]