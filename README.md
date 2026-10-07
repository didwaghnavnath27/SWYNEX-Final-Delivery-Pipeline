# SWYNEX Final Delivery Pipeline

## Task 4 - Final Delivery Pipeline

This project demonstrates a CI/CD-style final delivery pipeline using GitHub Actions and Docker.

## Pipeline Flow

Developer Push
        ↓
GitHub Repository
        ↓
GitHub Actions
        ↓
Checkout Source Code
        ↓
Build Docker Image
        ↓
Run Docker Container
        ↓
Verify Website
        ↓
Delivery Completed

## Technologies Used

- Git
- GitHub
- GitHub Actions
- Docker
- Nginx
- HTML
- CSS
- JavaScript

## Build

The GitHub Actions workflow builds the Docker image using the Dockerfile.

## Test

The Docker container is started on port 8080 and the website is verified using curl.

## Delivery

After successful build and verification, the workflow reports that the final delivery was completed successfully.

## Workflow File

The pipeline configuration is available at:

.github/workflows/cd.yml

## Result

The GitHub Actions workflow completed successfully, demonstrating a working CI/CD-style final delivery pipeline.

## Task 4

Completed as part of the SWYNEX internship.