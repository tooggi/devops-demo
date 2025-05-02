# devops-demo

## Description
This project is a simple web application that runs as a web server and displays graphics from an SVG file. The application is packaged into a Docker container for easy deployment and portability.

## Features
- Serves a web page displaying an SVG graphic.
- Lightweight and easy to deploy using Docker.

## Project Structure
- `Dockerfile`: Configuration for building the Docker container.
- `html/`: Contains the HTML and SVG files for the web page.
- `src/`: Contains the Go source code for the application.

## Getting Started

### Prerequisites
- Docker installed on your system.

### Build and Run
1. Build the Docker image:
   ```bash
   docker build -t devops-demo .
   ```
2. Run the Docker container:
   ```bash
   docker run -p 8080:8080 devops-demo
   ```
3. Open your browser and navigate to `http://localhost:8080` to view the application.

