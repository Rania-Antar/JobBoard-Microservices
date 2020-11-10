FROM openjdk:15
EXPOSE 8189
ADD /target/Job-0.0.1-SNAPSHOT.war docker-service-job.jar
ENTRYPOINT ["java", "-jar", "docker-service-job.jar"]