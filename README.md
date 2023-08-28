# My DevOps Project

This is a simple DevOps project that sets up a Flask web application using Docker and GitHub Actions for CI/CD.

## Project Structure

- `app/`: Contains the Flask web application code and Dockerfile.
- `.github/workflows/main.yml`: GitHub Actions workflow file for CI/CD.
- `README.md`: Project description.

## How to Run

1. Clone the repository.
2. Make changes to the application code in `app/app.py`.
3. Push the changes to the `main` branch.
4. GitHub Actions will automatically build and deploy the Docker image to Docker Hub.

