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

## My Contribution

Designed and configured the Jenkins CI pipeline and integrated build, testing, code-quality analysis, code coverage, SonarQube, and Nexus Repository into a single automated workflow.

## Pipeline Result

The pipeline successfully builds the application, executes tests, generates code-quality and coverage reports, sends analysis results to SonarQube, and publishes the WAR artifact to Nexus Repository.
