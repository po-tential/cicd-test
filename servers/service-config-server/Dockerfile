FROM openjdk:17-jdk-slim

COPY target/service-config-server.jar service-config-server.jar

ENTRYPOINT ["java","-jar","service-config-server.jar","--spring.profiles.active=production"]