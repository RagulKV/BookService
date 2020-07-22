FROM openjdk:8u131-jdk-alpine
EXPOSE 80
COPY ./target/BookService.jar BookService.jar 
ENTRYPOINT ["java","-jar","/BookService.jar"]