FROM openjdk:14-alpine
COPY target/micronaut-domain-service-*.jar micronaut-domain-service.jar
EXPOSE 8080
CMD ["java", "-Dcom.sun.management.jmxremote", "-Xmx128m", "-jar", "micronaut-domain-service.jar"]