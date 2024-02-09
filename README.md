# Reverse Proxy With Docker Compose

## Overview

This repository contains the Docker Compose configuration for running a .NET 8 application behind a NGINX reverse proxy. Docker Compose allows you to define and run multi-container Docker applications with ease.

## Prerequisites

- Docker: Ensure that Docker is installed on your machine. You can download and install Docker from [Docker's official website](https://www.docker.com/get-started).

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/felicksLindgren/reverse-proxy-with-docker-compose
    ```

2. Build and run the application using Docker Compose:

   ```bash
   docker-compose up --build
   ```

    The `docker-compose up` command will build the images and start the containers defined in the `docker-compose.yml` file. The `--build` flag is used to build the images before starting the containers.
3. Open your web browser and navigate to `https://localhost:8084`. You should see the application running behind the NGINX reverse proxy.
