# VProfile Jenkins CI/CD Pipeline

## Overview

Implemented a Jenkins-based CI pipeline for a Java web application with automated build, testing, code-quality analysis, and artifact publishing.

## CI/CD Pipeline

GitHub
   ↓
Jenkins
   ↓
Maven Build
   ↓
JUnit Tests
   ↓
JaCoCo
   ↓
Checkstyle
   ↓
SonarQube
   ↓
Nexus Repository

## Technologies

- Jenkins
- GitHub
- Maven
- JDK 17
- JUnit
- JaCoCo
- Checkstyle
- SonarQube
- Nexus Repository

## Pipeline Features

- Automated source-code checkout from GitHub
- Maven-based application build
- Automated unit testing
- Code coverage using JaCoCo
- Static code analysis using Checkstyle
- Code-quality analysis using SonarQube
- WAR artifact publishing to Nexus Repository
- Jenkins Pipeline automation

## What I Implemented

- Configured Jenkins declarative pipeline for automated CI.
- Integrated Maven and JDK 17 into Jenkins.
- Automated application build and WAR artifact generation.
- Added unit testing using Maven.
- Integrated JaCoCo for code coverage reporting.
- Integrated Checkstyle for static code analysis.
- Integrated SonarQube for centralized code-quality analysis.
- Configured Nexus Repository for storing versioned WAR artifacts.
- Used Jenkins credentials for secure Nexus authentication.

## Pipeline Result

The pipeline successfully builds the application, executes tests, generates code-quality and coverage reports, sends analysis results to SonarQube, and publishes the WAR artifact to Nexus Repository.

## Future Improvements

- Add SonarQube Quality Gate enforcement.
- Containerize the application using Docker.
- Push Docker images to a container registry.
- Add automated deployment to AWS.
- Add security scanning to the CI pipeline.
- Implement deployment and rollback strategies.
