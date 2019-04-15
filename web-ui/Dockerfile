FROM openjdk:8
ADD target/web-ui.jar web-ui.jar
EXPOSE 9000
ENTRYPOINT ["java", "-jar", "web-ui.jar"]