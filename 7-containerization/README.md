# Module 7: Containerization and Kubernetes

## Goal
Learn the core tools required to package and scale ML applications reliably.

## Learning outcomes

- use Docker confidently
- write production-friendly container definitions
- understand Kubernetes architecture and resources
- deploy applications with rollout and scaling controls
- work with configuration and secrets

## Topics

### Docker
- images, layers, and caching
- Dockerfile patterns
- multi-stage builds
- security best practices
- local development workflows

### Kubernetes basics
- pods, deployments, services, ingress
- namespaces, configmaps, secrets
- replica sets and rolling updates
- liveness and readiness probes
- autoscaling basics

### ML deployment patterns
- model serving in containers
- batch jobs in Kubernetes
- API-based inference services
- dependency management and isolation

### Operations
- logs and debugging
- health checks
- resource limits
- troubleshooting pod issues

## Exercises

- Build a Docker image for a FastAPI model API
- Deploy the app to a local Kubernetes cluster or equivalent environment
- Configure environment variables and secrets
- Explain rollback and scaling strategies

## Deliverable

Create a deployment package for a model API with:

- Dockerfile
- deployment manifest
- service manifest
- health-check configuration
- explanation of scaling and update strategy

