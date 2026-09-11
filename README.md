# CI/CD Final Project

## Project Overview

This project demonstrates the implementation of a complete **CI/CD (Continuous Integration and Continuous Deployment) pipeline** for a sample application.

The project applies automation and DevOps practices using **GitHub Actions, Tekton, and OpenShift Pipelines**. The pipeline is designed to automate code quality checks, run unit tests, build and deploy the application, and verify that the application is running successfully on OpenShift.

## Technologies Used

* GitHub
* GitHub Actions
* Flake8 / ESLint
* Nose / Jest
* Tekton
* OpenShift
* OpenShift Pipelines
* Kubernetes
* CI/CD

## Project Objectives

The main objectives of this project are to:

* Automate the software development workflow.
* Run linting and code-quality checks automatically.
* Execute unit tests automatically.
* Create and manage CI/CD tasks using Tekton.
* Build and deploy the application on OpenShift.
* Use OpenShift Pipelines to automate application deployment.
* Monitor pipeline execution and application logs.
* Verify that the deployed application is running successfully.

## CI/CD Pipeline

The CI/CD workflow includes the following major stages:

1. **Source Code** – The application source code is stored in GitHub.
2. **Linting** – GitHub Actions checks the source code using Flake8 or ESLint.
3. **Unit Testing** – Automated tests are executed using Nose or Jest.
4. **Tekton Tasks** – Tekton tasks manage pipeline operations such as cleanup and testing.
5. **Build** – The application is built as part of the OpenShift pipeline.
6. **Deployment** – The application is deployed to the OpenShift cluster.
7. **Verification** – Pipeline execution and application logs are checked to verify successful deployment.

## Expected Result

At the end of the project, the application should be successfully tested, built, deployed, and running on the OpenShift cluster through an automated CI/CD pipeline.

## Project Name

**CI/CD Final Project – OpenShift Pipeline**

## Author

Mahmoud Omari
