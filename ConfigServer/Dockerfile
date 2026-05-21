FROM eclipse-temurin:21-jdk

WORKDIR /app

COPY target/*SNAPSHOT.jar config-server.jar

ENTRYPOINT ["java","-jar","config-server.jar"]