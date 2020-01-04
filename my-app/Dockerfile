FROM java:8
WORKDIR /
ADD ./home/vsts/work/1/s/my-app/target/my-app-1.0-SNAPSHOT-shaded.jar my-app-1.0-SNAPSHOT-shaded.jar
EXPOSE 8080
CMD java - jar my-app-1.0-SNAPSHOT-shaded.jar