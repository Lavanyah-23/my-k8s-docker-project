# Hello from Kubernetes and Docker

A simple Flask app containerized with Docker and deployable to Kubernetes.

## How to Run

1. Build the Docker image:
   docker build -t hello-k8s-app .

2. Deploy with Kubernetes:
   kubectl apply -f k8s/deployment.yaml
