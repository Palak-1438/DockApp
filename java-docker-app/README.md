# Java Docker Application

This project demonstrates how to create a Docker container for a simple Java application.

## Project Structure

```
java-docker-app
├── src
│   └── main
│       └── java
│           └── App.java
├── Dockerfile
├── pom.xml
└── README.md
```

## Prerequisites

- Docker installed on your machine
- Maven installed on your machine

## Building the Docker Image

1. Navigate to the project directory:

   ```
   cd java-docker-app
   ```

2. Build the Docker image using the following command:

   ```
   docker build -t java-docker-app .
   ```

## Running the Docker Container

To run the Docker container, use the following command:

```
docker run java-docker-app
```

This will execute the Java application inside the Docker container. You should see the output from the application in your terminal.