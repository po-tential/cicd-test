FROM openjdk:17-jdk-slim

COPY target/embedded-keycloak-server.jar embedded-keycloak-server.jar

ENTRYPOINT ["java","-jar","embedded-keycloak-server.jar","--spring.profiles.active=production"]