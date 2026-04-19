Automated Docker Deployment Pipeline
This assignment demonstrates a fully automated CI/CD pipeline that builds and pushes a Docker image to Docker Hub whenever code is updated.

 Implementation Steps
1. Repository & Local Setup
GitHub Creation: Created the docker-task repository on GitHub and cloned it to the local environment.

App Development: Created app.py and a Dockerfile in VS Code to containerize the application logic.

2. Docker Hub Configuration
Access Token: Generated a Personal Access Token (PAT) on Docker Hub with Read, Write, Delete permissions for secure CLI access.

Registry Setup: Verified the repository path at idongesitbassey/docker-task.

3. GitHub Actions CI/CD
Workflow File: Created .github/workflows/github-actions-demo.yml to define the automation steps.

 Added encrypted credentials under GitHub Settings > Secrets:

DOCKERHUB_USERNAME: idongesitbassey

DOCKERHUB_TOKEN: (The secure PAT).

4. Deployment & Verification
Automation: Pushed changes from VS Code to GitHub, triggering the workflow.

 Verified the "Build and Push" completion in the GitHub Actions tab and confirmed the image availability on Docker Hub.


