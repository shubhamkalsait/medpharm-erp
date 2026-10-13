FROM maven:3.9.6-eclipse-temurin-17

COPY . .

RUN mvn clean package -DskipTests

EXPOSE 8082

CMD ["java", "-jar", "target/product-service-1.0.0.jar"]
