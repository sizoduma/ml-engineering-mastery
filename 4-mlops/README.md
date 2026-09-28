# Module 4: MLOps and Production ML

## Goal
Learn how to move from experimental notebooks to production-ready ML systems.

## Learning outcomes

- define MLOps best practices
- track experiments and artifacts
- version data and models
- build CI/CD for ML projects
- monitor drift and model performance
- design retraining and governance patterns

## Topics

### MLOps foundations
- why MLOps matters
- ML lifecycle stages
- experimentation to deployment pipeline
- ownership and governance

### Experiment tracking
- MLflow basics
- parameters, metrics, and artifacts
- model registry
- experiment comparison

### Data and model versioning
- versioning for data and schemas
- model lineage
- reproducibility principles
- immutable artifacts

### CI/CD for ML
- linting and validation
- unit tests for data contracts and pipelines
- automated model training jobs
- deployment gates
- release promotion strategies

### Monitoring and operations
- model drift
- data drift
- performance degradation
- logging and observability
- alerting and incident response

### Production concerns
- latency and throughput
- reliability
- retraining triggers
- rollback strategies
- model governance

## Exercises

- Set up an MLflow tracking server and log experiments
- Create a reproducible pipeline with versioned data
- Design a CI/CD workflow for retraining and deployment
- Build a drift-monitoring checklist for an ML system

## Deliverable

Create a complete MLOps workflow for a small project:

- train a model
- log it to MLflow
- validate a deployment candidate
- build a simple deployment process
- define monitoring steps and alerting criteria

