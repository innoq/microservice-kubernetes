FROM adoptopenjdk/openjdk11:alpine-jre
COPY target/microservice-kubernetes-demo-order-0.0.1-SNAPSHOT.jar /microservice-kubernetes-demo-order-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-Xmx400m", "-Xms400m", "-XX:+UseContainerSupport", "-Djava.security.egd=file:/dev/./urandom","-jar","/microservice-kubernetes-demo-order-0.0.1-SNAPSHOT.jar"]

EXPOSE 8080
