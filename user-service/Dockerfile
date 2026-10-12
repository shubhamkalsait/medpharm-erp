FROM maven:3.8.3-openjdk-17

WORKDIR /opt

COPY . .

RUN mvn clean package -DskipTest

EXPOSE 8081

ENTRYPOINT [ "java", "-jar", "target/*.jar" ]