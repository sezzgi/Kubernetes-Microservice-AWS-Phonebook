# Kubernetes-microservice-aws-phonebook

A cloud-native phonebook application showcasing microservices architecture and container orchestration on AWS.

## Project Highlights

✨ Advanced cloud architecture using Kubernetes and Docker  
✨ Scalable microservices with automated deployment  
✨ Production-grade security and data persistence  
✨ Infrastructure as Code implementation

## Key Features

• High Availability
  - Automated scaling
  - Load balancing
  - Persistent data storage

• Security
  - Kubernetes secrets management
  - Secure service communication
  - Protected database access

• Modern Architecture
  - Microservices design
  - Container orchestration
  - Cloud-native deployment


## Quick Start

1. **Setup Infrastructure**
   ```bash
   aws cloudformation deploy --template-file k8s-cluster.yaml
   ```

2. **Deploy Application**
   ```bash
   kubectl apply -f k8s/
   ```

3. **Access Application**
   - Main Interface: `http://[hostname]:30001`
   - Search Interface: `http://[hostname]:30002`
