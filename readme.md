# Simple Go API Container

This repository contains a simple Go-based API application designed to demonstrate containerization using Docker. The project is structured to provide a straightforward example of how to build, run, and deploy a Go application in a containerized environment.

## Features

- A basic REST API written in Go.
- Dockerfile for containerizing the application.
- Instructions for building and running the container.
- Lightweight and easy to understand for beginners.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Go](https://golang.org/dl/) (latest stable version recommended)
- [Docker](https://www.docker.com/get-started)

## Project Structure

```
simple-go-api-container/
├── main.go          # The main application code
├── Dockerfile       # Dockerfile to build the container image
├── README.md        # Documentation for the project
└── .dockerignore    # Files and directories to ignore during Docker build
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/simple-go-api-container.git
cd simple-go-api-container
```

### 2. Build the Docker Image

```bash
docker build -t simple-go-api .
```

### 3. Run the Container

```bash
docker run -p 8080:8080 simple-go-api
```

### 4. Access the API

Once the container is running, you can access the API at `http://localhost:8080`.

## Customization

Feel free to modify the `main.go` file to add more endpoints or customize the API logic. Rebuild the Docker image after making changes.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

