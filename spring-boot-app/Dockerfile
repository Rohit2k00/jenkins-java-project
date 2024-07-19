FROM openjdk:21

WORKDIR /opt/app 

ARG file=target/*.jar

COPY ${file} app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
