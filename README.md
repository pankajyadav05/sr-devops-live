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

# Assignment: Deploy a Web Application using CI/CD and Kubernetes [ESTD. Time to finish task: 75 to 90 mins]

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
