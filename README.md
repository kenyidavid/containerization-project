# containerization-project
Operating system Task One
# Containerization Project

This project demonstrates containerization using Docker and Kubernetes.

## Technologies Used

- Python Flask
- Docker
- Kubernetes
- Git

## Running the Application

### Build Docker Image

docker build -t flask-app .

### Run Container

docker run -p 5000:5000 flask-app

### Kubernetes Deployment

kubectl apply -f deployment.yaml

kubectl apply -f service.yaml
