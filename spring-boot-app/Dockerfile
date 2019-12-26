FROM java:8
COPY /var/lib/jenkins/workspace/Spring-Boot-Docker/spring-boot-app/target/spring-boot-app-0.0.1-SNAPSHOT.jar /app.jar
CMD ["java" , "-jar" , "-Dspring.profiles.active=default", "spring-boot-app.jar"]
