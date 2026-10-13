FROM maven:3.8.3-openjdk-17

COPY . .

RUN mvn clean package -DskipTests

EXPOSE 8082

CMD ["java", "-jar", "target/product-service-1.0.0.jar"]
