FROM java:8
COPY ./target/my-app-1.0-SNAPSHOT-shaded.jar /my-app-1.0-SNAPSHOT-shaded.jar

CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=test", "/my-app-1.0-SNAPSHOT-shaded.war"]




