# Flask App with CI/CD Pipeline

## Problem Statement
Manual deployment of applications is time-consuming and error-prone. We need an automated way to test, build, and deploy our Flask application when code changes are pushed.

## Solution
This project demonstrates how to implement automated CI/CD (Continuous Integration/Continuous Deployment) for a simple Flask web application using GitHub Actions and Docker.

## Process
1. Create a simple Flask application
2. Write tests to verify functionality
3. Containerize the application with Docker
4. Set up GitHub Actions workflow to automate testing and deployment
5. Configure pipeline to push Docker image to DockerHub

## Tools Used
- **Python/Flask**: For the web application
- **Pytest**: For automated testing
- **Docker**: For containerization
- **GitHub Actions**: For CI/CD pipeline
- **DockerHub**: For Docker image repository

## Setup Instructions
1. Clone this repository
2. Add DockerHub credentials as GitHub repository secrets
3. Push changes to the main branch to trigger the CI/CD pipeline.
