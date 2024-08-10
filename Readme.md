# Spring Boot with Docker

## Getting Started

- run the application without the Docker container
```
./gradlew bootRun
```

- run the application with the Docker container
```
./gradlew bootBuildImage --imageName=vkpro/docker-spring-boot
docker run -p 8080:8080 -t vkpro/docker-spring-boot
```
