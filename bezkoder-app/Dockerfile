# FROM maven:3.8.5-openjdk-17 # for Java 17
FROM maven:3.8.2-jdk-8

WORKDIR /bezkoder-app
COPY . .
RUN mvn clean install

CMD mvn spring-boot:run