# How to deploy an OpenSage agent to a production environment

_Use a containerization tool like Docker to deploy the agent_

## Steps

1. Create a Dockerfile for the OpenSage agent using the `opensage docker` command
2. Build the Docker image using the `docker build` command
3. Push the image to a container registry like Docker Hub
4. Deploy the image to a production environment using a tool like Kubernetes
5. Monitor the agent's performance using logging and monitoring tools

## Pitfalls

- Not configuring the Dockerfile correctly before building the image