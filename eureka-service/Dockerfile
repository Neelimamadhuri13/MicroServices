FROM openjdk:11.0-jdk
ADD ./target/eureka-0.0.1-SNAPSHOT.jar /muzix/app/eureka-0.0.1-SNAPSHOT.jar
WORKDIR muzix/app
EXPOSE 9091
ENTRYPOINT ["java", "-jar", "eureka-0.0.1-SNAPSHOT.jar"]
