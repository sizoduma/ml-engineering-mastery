# Module 9: APIs and Microservices for ML

## Goal
Learn how to expose machine learning capabilities as reusable and production-ready APIs.

## Learning outcomes

- design REST APIs for ML systems
- implement model serving endpoints
- create API validation and error handling
- understand asynchronous and scalable service patterns
- deploy API services with monitoring

## Topics

### API design
- resource modeling
- HTTP methods and semantics
- input/output schemas
- idempotency and error handling
- API versioning

### FastAPI and Python service patterns
- request validation
- async endpoints
- dependency injection
- Pydantic models
- logging and metrics

### ML API deployment
- model loading and caching
- performance optimization
- batching and concurrency handling
- resilience and timeouts

### Microservice thinking
- service boundaries
- contracts and integration patterns
- reducing coupling between training and inference services

## Exercises

- Build a FastAPI app that serves a trained model
- Validate input schemas and error cases
- Benchmark latency under concurrent requests
- Add logging and basic observability

## Deliverable

Create a service with:

- API contract
- model inference endpoint
- health checks
- configuration management
- deployment notes for production

