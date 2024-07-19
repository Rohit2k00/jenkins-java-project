FROM openJDK:21

WORKDIR /opt/app 

COPY target/spring-boot-web.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
