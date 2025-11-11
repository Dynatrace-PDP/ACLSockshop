FROM openjdk:8u92-alpine

WORKDIR /usr/src/app
COPY ./target/*.jar ./app.jar

ENTRYPOINT ["java","-jar","./app.jar", "--port=8080"]
