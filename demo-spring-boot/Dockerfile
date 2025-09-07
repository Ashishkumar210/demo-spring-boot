FROM eclipse-temurin:21-jdk-alpine
RUN apk add curl
VOLUME /tmp
EXPOSE 9094
ADD target/spring-boot-aws-deploy-service.jar spring-boot-aws-deploy-service.jar
ENTRYPOINT ["java","-jar","/spring-boot-aws-deploy-service.jar"]
