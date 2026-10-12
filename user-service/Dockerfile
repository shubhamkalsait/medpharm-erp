FROM maven:3.9.12-eclipse-temurin-17-alpine

WORKDIR /opt

COPY . .

RUN mvn clean package -DskipTests

EXPOSE 8081

ENTRYPOINT [ "java", "-jar", "target/user-service-1.0.0.jar" ]