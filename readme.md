# BrFilmes

This repository contains a full-stack application developed using Docker Compose. It consists of multiple services, including a frontend and a backend, orchestrated and deployed using Docker Compose.

## Features

- Frontend: Angular 16
- Backend: NestJs, mongoose
- Database: MongoDb

## Prerequisites

Before running the application, ensure that you have the following prerequisites installed on your machine:

- Docker
- Docker Compose
## Getting Started

To run the BRFilmes, follow these steps:

1. Clone this repository:

  ```bash
  git clone --recursive <repository-url>
  cd <repository-directory>
  ```

3. Build and start the application using Docker Compose:

   ```bash
   docker-compose up -d
   ```

   This command will build and start the containers defined in the `docker-compose.yml` file.

4. Access the application:

   - Frontend: http://localhost
   - Backend: http://localhost:3000


## Disclaimer

This project was developed as part of a technical test, and certain decisions were made for the sake of expediency and learning. 
The .env file was intentionally included in the root of the repository, and it is advised to handle sensitive information with caution. Additionally, the frontend page was built within a single day while I was in the process of learning Angular for the first time. 
As a result, some aspects of the code may not be optimal or fully aligned with best practices. Due to time constraints, extensive refactoring and in-depth exploration of certain concepts were not possible. 
Nevertheless, I take pride in successfully achieving the intended functionality of the project.

