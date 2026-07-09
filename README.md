# CI/CD with GitHub Actions
Spring Boot app build-test , docker-build-image
on push

# What this workflow does
  - Checks out your repository.
  - Installs Java 21.
  - Builds the Spring Boot application using Maven.
  - Logs in to Docker Hub.
  - Builds the Docker image.
  - Pushes the Docker image to Docker Hub
