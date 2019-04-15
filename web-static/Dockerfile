FROM openjdk:8
ADD target/web-static.jar web-static.jar
EXPOSE 9000
ENTRYPOINT ["java", "-jar", "web-static.jar"]