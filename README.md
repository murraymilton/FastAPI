# <div align="center"><h1>FastAPI Mastery Course</h1></div>


# FastAPI: The Complete Course Project

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)


Welcome to my repository for the project I developed while taking [FastAPI: The Complete Course](https://www.udemy.com/course/fastapi-the-complete-course/learn/lecture/29025340) on Udemy. This course was a deep dive into building high-performance, data-driven web applications using FastAPI, one of the fastest-growing Python web frameworks. Here, I've applied what I learned to create a fully functional API project that demonstrates best practices, testing, and deployment strategies.

## Project Overview

This project is a comprehensive application that serves as a testament to my understanding and skill in developing with FastAPI. It includes user authentication, database interactions, advanced patterns, and deployment techniques. Here's a brief overview of what I've accomplished:

- **API Development**: Developed RESTful APIs for a mock e-commerce platform, including endpoints for user registration, authentication, product management, and orders.
- **Data Models**: Implemented robust Pydantic models to ensure data validation and serialization.
- **Database Integration**: Integrated PostgreSQL for data persistence, utilizing SQLAlchemy for ORM-based interactions.
- **Security**: Added OAuth2 with JWT tokens for secure authentication and authorization.
- **Testing**: Wrote comprehensive unit and integration tests using Pytest to ensure reliability and performance.
- **Dockerization**: Containerized the application using Docker to streamline deployment and scaling.
- **CI/CD**: Setup GitHub Actions for continuous integration and deployment, automating the testing and deployment pipeline.

## Technologies Used

- **FastAPI**: For building efficient and scalable web APIs.
- **Pydantic**: For data validation and settings management.
- **SQLAlchemy**: For ORM-based database interactions.
- **OAuth2 & JWT**: For implementing authentication and authorization.
- **Docker**: For containerizing the application and ensuring consistent environments.
- **GitHub Actions**: For automating the workflow of testing and deployment.

## How to Run

#bash
docker-compose up --build


### Feature Highlights

- **Real-Time Communication**: Implements WebSocket connections for instant messaging between users.
- **Scalable Architecture**: Designed to handle numerous concurrent connections, ensuring a responsive and reliable chat experience.
- **Seamless Integration**: Fully integrated with the existing user authentication system to maintain security and user privacy.
- **Frontend Compatibility**: Developed a simple frontend demonstration using React to showcase the real-time chat functionality.

### Implementation Details

The chat feature utilizes FastAPI's WebSocket support to establish a full-duplex communication channel between the server and the client. Messages are sent and received in real-time, with the server acting as the central hub for message distribution among connected clients.
