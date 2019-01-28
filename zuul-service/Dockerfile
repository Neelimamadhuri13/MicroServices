FROM openjdk:11.0-jdk
ADD ./target/zuul-service-0.0.1-SNAPSHOT.jar /muzix/app/zuul-service-0.0.1-SNAPSHOT.jar
WORKDIR muzix/app
ENTRYPOINT ["java", "-jar", "zuul-service-0.0.1-SNAPSHOT.jar"]
EXPOSE 8085
