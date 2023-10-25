FROM openjdk:17
EXPOSE 8082
ADD target/rating-service.jar rating-service.jar
ENTRYPOINT [ "java","-jar","/rating-service.jar" ]