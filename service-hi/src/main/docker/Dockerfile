FROM gmaslowski/jdk:latest
VOLUME /data/eureka-service-center/client
ADD service-hi-0.0.1-SNAPSHOT.jar app.jar
#RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
