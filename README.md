![image](https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo.png&w=1200&q=75)

# Assignment: Deploy a Web Application using CI/CD and Docker

In this assignment, using simple web application with a backend (e.g., Python) and a frontend (e.g., React). Your task is to set up a CI/CD pipeline and deploy the application using Docker containers.

## Requirements:

1. **CI/CD Pipeline**: Set up a CI/CD pipeline using a tool of your choice (e.g., GitHub Actions, GitLab CI/CD, Jenkins, CircleCI, etc.). The pipeline should automatically build, test (Front-end) and deploy the application when changes are pushed to main branch of the repository.

   #### To run tests (FE)

   ```bash
   npm test
   ```

   #### To make build (FE)

   ```bash
   npm build
   ```

2. **Docker Containerization**: Create Docker images for the backend and frontend components of the application. The images should be built and pushed to a container registry (e.g., Docker Hub, GitHub Container Registry, or a private registry) as part of the CI/CD pipeline.

3. **Infrastructure as Code (IAC)**: Use an IAC tool (e.g., Terraform, Ansible, or CloudFormation) to provision the necessary infrastructure for deploying the containerized application. This could include creating a Virtual Machine (VM), setting up a container runtime (e.g., Docker Engine), or deploying to a managed container service (e.g., AWS ECS, Google Cloud Run, or Azure Container Instances).

4. **Deployment**: Deploy the containerized application to the provisioned infrastructure using the IAC tool. Ensure that the application is accessible and functioning correctly.

5. **Documentation**: Provide clear documentation explaining the steps you took to set up the CI/CD pipeline, build and push the Docker images, provision the infrastructure, and deploy the application.

## Bonus: Kubernetes Deployment

If you have experience with Kubernetes, you can optionally deploy the containerized application to a Kubernetes cluster. This could involve using an IAC tool to provision the Kubernetes cluster and then deploying the application using Kubernetes manifests or a tool like Helm.

## Submission:

Once you've completed the assignment, please submit your work by providing:

1. Provide the GitHub repository URL as a PRIVATE Git repository (also provide access) to roshan@gitforcetalent.com and cc prithvi@gitforcetalent.com, pankaj@gitforcetalent.com
2. Instructions on how to access and test the deployed application.
3. Provide any additional notes or considerations regarding the implementation.

## Evaluation Criteria:

Your submission will be evaluated based on the following criteria:

- Successful implementation of the CI/CD pipeline and Docker containerization.
- Proper use of Infrastructure as Code (IAC) principles and tools.
- Successful deployment of the containerized application to the provisioned infrastructure.
- Clear and well-documented steps for setting up the CI/CD pipeline, building Docker images, provisioning infrastructure, and deploying the application.
- (Bonus) Successful deployment of the containerized application to a Kubernetes cluster.

### Check full details about Evaluation criteria here [marks.md](MARKS.md)
