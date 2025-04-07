# nodejs-demo-app
TASK 1: Automate Code Deployment Using CI/CD Pipeline (GitHub Actions) • Objective: Set up a CI/CD pipeline to build and deploy a web app. In this project, we leverage Jenkins to create a robust CI/CD pipeline that integrates tools like Docker, and OWASP Dependency Check to deliver secure and high-quality software. Tools used:

GitHub
Jenkins
Docker Hub
Docker
nodeJS
GITHUB: GitHub is a platform for hosting and sharing code using Git. It helps developers collaborate by tracking changes, managing versions, and reviewing code. You can create repositories(repos) to store and organize projects. It also offers features like issue tracking and CI/CD workflows.

JENKINS: Jenkins is an automation tool for building and deploying software. It uses pipelines to automate tasks like testing, building, and deploying code. It supports plugins to integrate with various tools. Jenkins makes Continuous Integration and Continuous Delivery (CI/CD) easy.

DOCKER: Docker is a tool to create, share, and run lightweight virtualized environments called containers. Containers package code and dependencies together for consistent behavior across systems. It simplifies app deployment and avoids “it works on my machine” issues. Docker images are reusable blueprints for containers.

NODE.JS: Node.js is a runtime that lets you run JavaScript outside the browser. It’s great for building fast and scalable server-side applications. Node.js uses non-blocking, event-driven programming for high performance. It’s commonly used for web servers, APIs, and real-time apps.

CI/CD WORKFLOW: • The pipeline automates build, test, and deploy processes, making it efficient and reliable. • Security and quality checks are seamlessly integrated into the pipeline, ensuring every release is both secure and robust.

STEP-1: Launch EC2 Instance with below Configurations

AMI : Amazon Linux Kernel 5.10
Instance Type: T2.small
EBS Volume : 28 GB
Security Groups : All Traffic
STEP-2: Install Jenkins

STEP-3: Install Docker & GIT

#chmod 777 ///var/run/docker.sock

STEP-4: Install the following dependencies on Jenkins

NodeJS (version 16.2.0)
Docker Pipeline
pipeline stageview
STEP-5: Integrate all the tools to Jenkins

STEP-6: Add Dockerhub Credentials

STEP-7: Create a Jenkins Job

STEP-8: Docker hub registry image

STEP-9: Finally Deployed website with public IP and port number. http://18.232.116.59:3000/
