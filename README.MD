# Docker Test App

This repository contains a simple application to demonstrate the use of Docker for containerization.

## Features

- Lightweight and easy to use.
- Demonstrates Dockerfile and Docker Compose usage.
- Includes a sample application for testing.

## Prerequisites

- [Docker](https://www.docker.com/) installed on your system.
- [Docker Compose](https://docs.docker.com/compose/) installed (if using `docker-compose.yml`).

## Getting Started

1. Clone the repository:
    
    git clone https://github.com/HimanshuKumar101/Docker_Project.git
    cd docker-testapp
    ```

2. Build the Docker image:

    docker build -t docker-testapp .
    ```

3. Run the container:

    docker run -p 8080:8080 docker-testapp
    ```

4. Access the application in your browser at `http://localhost:8080`.

## Using Docker Compose

1. Start the application with Docker Compose:

    docker-compose up
    ```

2. Stop the application:
    
    docker-compose down
    ```

## Project Structure

```
docker-testapp/
├── Dockerfile
├── docker-compose.yml
├── app/
│   ├── main.py
│   ├── requirements.txt
├── README.md
```

- `Dockerfile`: Instructions to build the Docker image.
- `docker-compose.yml`: Configuration for Docker Compose.
- `app/`: Contains the application code.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
