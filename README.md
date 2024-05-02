<div align="center">
	<a target="_blank" href="https://gitforcetalent.com">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo-light.png&w=1920&q=75">
            <source media="(prefers-color-scheme: light)" srcset="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo.png&w=1920&q=75">
            <img alt="https://gitforcetalent.com" src="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo.png">
        </picture>
	</a>
    <br />
    <br />
</div>

---

---

# Assignment: Deploy a Web Application using CI/CD and Kubernetes

In this assignment, using simple web application with a backend (e.g., Python) and a frontend (e.g., React). Your task is to set up a CI/CD pipeline and deploy the application using Kubernetes cluster.

## Requirements:

1. **CI/CD Pipeline**: Set up a CI/CD pipeline using either Jenkins or GitLab CI/CD. The pipeline should automatically build, test (Front-end), and deploy the application when changes are pushed to the main branch of the repository.

   #### To run tests (FE)

   ```bash
   npm test
   ```

   #### To make build (FE)

   ```bash
   npm build
   ```

2. **Kubernetes Deployment**: Create Docker images for the backend and frontend components of the application. The images should be built and pushed to a container registry (e.g., Docker Hub, GitHub Container Registry, or a private registry) as part of the CI/CD pipeline. Deploy the containerized application to a Kubernetes cluster.

3. **Infrastructure as Code (IAC)**: Use either Terraform or Ansible to provision the necessary infrastructure for deploying the Kubernetes cluster and the containerized application.

4. **Logging and Monitoring**: Implement logging and monitoring for the deployed application using one of the following solutions: Grafana, ELK Stack (Elasticsearch, Logstash, Kibana), or Prometheus.

5. **Documentation**: Provide clear documentation explaining the steps you took to set up the CI/CD pipeline, build and push the Docker images, provision the infrastructure (including the Kubernetes cluster), deploy the application to Kubernetes, and implement logging and monitoring.

## Submission:

Once you've completed the assignment, please submit your work by providing:

1. Provide the GitHub repository URL as a PRIVATE Git repository (also provide access) to pankaj@gitforcetalent.com and cc prithvi@gitforcetalent.com, roshan@gitforcetalent.com, shibasweta@gitforcetalent.com.
2. Instructions on how to access and test the deployed application.
3. Provide any additional notes or considerations regarding the implementation.

## Evaluation Criteria:

Your submission will be evaluated based on the following criteria:

- Successful implementation of the CI/CD pipeline and containerization.
- Proper use of Infrastructure as Code (IAC) principles and tools.
- Successful deployment of the containerized application to the provisioned infrastructure.
- Clear and well-documented steps for setting up the CI/CD pipeline, building Docker images, provisioning infrastructure, and deploying the application.

### Check full details about Evaluation criteria here [marks.md](MARKS.md)
