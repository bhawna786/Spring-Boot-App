FROM java:8
COPY target/spring-boot-app-0.0.1-SNAPSHOT.jar /root/spring-docker-application/spring-boot-app.jar
CMD ["java" , "-jar" , "-Dspring.profiles.active=default", "spring-boot-app.jar"]
