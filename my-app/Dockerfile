FROM java:8
COPY ./${JAR_FILE} app.jar

CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=test", "/my-app-1.0-SNAPSHOT-shaded.war"]




