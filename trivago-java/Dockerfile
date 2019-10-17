FROM openjdk
COPY java-webserver.jar /usr/app/
WORKDIR /usr/app
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "java-webserver.jar"]
