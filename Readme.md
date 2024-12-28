# Phonebook Microservices

## Project Overview

This project demonstrates:

- Real-world microservice architecture implementation
- Production-ready containerization practices
- Enterprise-grade data persistence and security
- Cloud infrastructure automation
- Modern DevOps workflows

## What The Application Does

The Phonebook application provides a practical example of splitting a traditional monolithic application into microservices. It features:

- A frontend service for searching contacts
- A backend service for managing contacts (create, update, delete)
- A dedicated database service for data persistence
- RESTful API architecture
- Secure data handling and storage

## Technical Highlights

### Architecture & Infrastructure
- Kubernetes-orchestrated microservices
- MySQL database with persistent storage
- Load-balanced services with automatic scaling
- ConfigMaps and Secrets for secure configuration management
- AWS cloud infrastructure managed through CloudFormation

### Security & Best Practices
- Containerized services with Docker
- Secure secret management
- Network isolation between services
- Infrastructure as Code (IaC) implementation
- GitOps-ready deployment configuration

### Technologies Used
- **Container Orchestration**: Kubernetes
- **Containerization**: Docker
- **Backend**: Python Flask
- **Database**: MySQL 5.7
- **Cloud Platform**: AWS
- **Infrastructure as Code**: CloudFormation
- **Version Control**: Git/GitHub



## Technical Architecture

The application is structured into three main components:

1. **Frontend Service (Search)**
   - Handles contact search operations
   - Exposed on port 30002
   - Horizontally scalable

2. **Backend Service (Create/Update/Delete)**
   - Manages contact modifications
   - Exposed on port 30001
   - Independently scalable from search service

3. **Database Service**
   - Persistent MySQL database
   - Protected within cluster
   - Automated backup and recovery capabilities


By implementing this project, developers demonstrate their ability to build and manage modern, cloud-native applications using industry-standard tools and practices.
