# cncf-ci-cd

## Introduction

- [Source](https://landscape.cncf.io/card-mode?category=continuous-integration-delivery)
- CI automates code changes by building and testing code
- CD pushes artifacts through deployment process
- Integrating code on a regular basis catches errors early on 
- Kubernetes introduces new challenges for CI/CD tooling
- Cloud-native CI/CD systems leverage k8s itself to build, run and manage CI/CD process
- In general, projects are either:
  1. CI systems
  2. CD systems
  3. Tools that help CD decide if code is ready to be pushed to prod
  4. Combination of all three (e.g., Spinnaker and Argo)

## Tools

| Tool | Status | Wiki | Summary | Hands-On |
|------|--------|------|---------|----------|
| Argo CD | Graduated | [Link](https://github.com/cheuklau/cncf-ci-cd/wiki/Argo-cd) | k8s-native GitOps CD | Yes |
| Argo Events | Graduated | [Link](https://github.com/cheuklau/cncf-ci-cd/wiki/Argo-Events) | k8s-native event-based trigger | Yes |
| Argo Workflows | Graduated | [Link](https://github.com/cheuklau/cncf-ci-cd/wiki/Argo-Workflows) | k8s-native version of Airflow | Yes |
