FROM openjdk:11
LABEL maintainer="jagatw"
ADD target/docker-spring-boot-2.6.3.jar springboot-docker-image.jar
ENTRYPOINT ["java","-jar","springboot-docker-image.jar"]