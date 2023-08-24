#define docker image
#FROM java:8
FROM adoptopenjdk/openjdk11:alpine-jre
Label maintainer="madhavan"
ADD target/restful-spring-example-0.0.1-SNAPSHOT.jar restful-spring-example-0.0.1-SNAPSHOT..jar
ENTRYPOINT [ "java","-jar","restful-spring-example-0.0.1-SNAPSHOT..jar"]