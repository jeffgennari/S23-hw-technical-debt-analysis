FROM java:8
WORKDIR /app
COPY build/libs/tartan-1.0-SNAPSHOT.jar /app
COPY config.docker.yml /app
EXPOSE 8080
EXPOSE 8081
CMD ["java", "-jar","tartan-1.0-SNAPSHOT.jar","server","config.docker.yml"]
