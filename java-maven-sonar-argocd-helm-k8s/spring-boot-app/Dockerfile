# You can change this base image to anything else
# But make sure to use the correct version of Java
FROM adoptopenjdk/openjdk11:alpine-jre



ADD target/spring-boot-web.jar target/spring-boot-web.jar


# This should not be changed
ENTRYPOINT ["java","-jar","/spring-boot-web.jar"]
