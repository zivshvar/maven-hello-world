FROM java:8
ADD ./${JAR_FILE} my-app.jar
EXPOSE 8080
CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=test", "/my-app.jar"]
