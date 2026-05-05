# DevOps Lifecycle Implementation

## Overview
End-to-end DevOps pipeline implementation using AWS, Ansible, Jenkins, Docker and GitHub.

## Architecture
- 3 AWS EC2 instances (Jenkins Master, Build Slave, Prod Server)
- Ansible for configuration management
- Jenkins for CI/CD pipeline
- Docker for containerization
- GitHub webhook for auto-triggering

## Pipeline Flow
- Push to develop → build + test only
- Push to master → build + test + deploy to production

## Tech Stack
AWS | Ansible | Jenkins | Docker | GitHub
