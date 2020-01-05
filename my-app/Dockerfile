FROM java:8
ADD ./${my-app-1.0-SNAPSHOT-shaded.jar} my-app.jar
EXPOSE 8080
CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=test", "/my-app.jar"]
