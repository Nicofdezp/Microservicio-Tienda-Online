FROM openjdk:8-jdk-alpine

COPY target/store-product-0.0.1-SNAPSHOT.jar /store-product/

EXPOSE 9012

WORKDIR /store-product

ENTRYPOINT java -jar store-product-0.0.1-SNAPSHOT.jar
