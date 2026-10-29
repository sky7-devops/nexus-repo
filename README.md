
# Nexus — Tericsoft DevOps Assessment

A static web application packaged with Docker and deployed on AWS EC2,
with an additional deployment to Amazon ECS.

## Technology Stack

- HTML and CSS
- Nginx
- Docker
- Amazon EC2
- Amazon ECR
- Amazon ECS with AWS Fargate
- Git and GitHub


### Why I Chose This Instance Size
Explain why t2.micro is sufficient for your lightweight
Nginx and Docker application and helps keep costs low.

## Run Locally

Build the Docker image:

    docker build -t nexus:1.0 .

Run the container:

    docker run --name cloud-hello -d -p 8081:8081 nexus:1.0

Open http://localhost:8081 in your browser.

Stop and remove the local container:

    docker rm -f cloud-hello

