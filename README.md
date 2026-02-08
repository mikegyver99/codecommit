## Lab Stages

The demo is divided into the following progressive stages:

1. **STAGE 0: Introduction & Setup**  
   Overview of the architecture, prerequisites, and lab goals.

2. **STAGE 1: Security & CodeCommit**  
   Configure IAM roles/policies, security best practices, and create a CodeCommit repository.

3. **STAGE 2: CodeBuild & ECR**  
   Set up CodeBuild to clone the repo, build a Docker container image, and push it to Amazon ECR.

4. **STAGE 3: CodePipeline Automation**  
   Create a CodePipeline with source (commit) and build stages to automatically trigger builds on every code commit.

5. **STAGE 4: ECS Fargate Deployment**  
   Provision an ECS Cluster, Target Groups, Application Load Balancer (ALB), and extend the pipeline to deploy to ECS Fargate.

6. **STAGE 5: Cleanup**  
   Instructions to safely delete all created resources to avoid unnecessary charges.

## Original Course Reference

This lab follows the advanced demo from Adrian Cantrill's AWS training:

- Course: [AWS Certified Developer - Associate](https://learn.cantrill.io/) (or related DevOps content)
- Lecture: [Advanced Demo – CI/CD Pipeline to ECS Fargate](https://learn.cantrill.io/courses/1101194/lectures/40856335)

