FROM openjdk:8
VOLUME /tmp/docker-spring-app
ADD /target/docker-spring-app.jar /durga/docker-spring-app.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","docker-spring-app.jar"]