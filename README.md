# Project Overview:
The project aims to illustrate the process of containerizing the '2048' game using Docker and subsequently deploying it on the AWS cloud infrastructure via Elastic Beanstalk. The primary objectives include demonstrating the Dockerization of an application, creation of a Docker image, local deployment, and ultimately, the cloud-based deployment of the containerized application using AWS services.

### Key Phases and Actions:

1) Dockerization Process:
- Utilization of a Dockerfile to define the construction of the Docker image.
- Incorporation of Ubuntu 22.04 as the base image.
- Installation and configuration of essential utilities (e.g., nginx, zip, curl).
- Configuration of the nginx server to facilitate game hosting.
- Acquisition and extraction of the game repository content from GitHub.
- Exposition of the application on Port 80 within the container.

2) Local Deployment:
- Construction of a Docker image from the Dockerfile.
- Execution of a local Docker container to locally host and enable interaction with the game.

3) AWS Deployment via Elastic Beanstalk:
- Access to the AWS Management Console.
- Establishment of an Elastic Beanstalk environment designed for Docker application deployment.
- Upload of the Dockerfile and associated artifacts to Elastic Beanstalk.
- Configuration of fundamental parameters for the application deployment.
- Leveraging Elastic Beanstalk for automated infrastructure provisioning.
- Accessing the deployed application via the provided CNAME.

<br>


Game GitHub repository https://github.com/gabrielecirulli/2048