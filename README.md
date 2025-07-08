# Kubernetes Manifests & Monitoring Setup

This repository contains all the Kubernetes manifests used to deploy a microservices-based application stack, along with the Helm-rendered monitoring configuration for Prometheus, Grafana, and Loki.

---
## What’s Included

### Core Microservices

- API Gateway
- Eureka Server
- Email Service
- KYC Service & Frontend
- Report Service & Frontend

All deployed using Kubernetes Deployments, Services, and Ingress resources.

### Monitoring Stack

Installed via Helm:

- Prometheus & Grafana using `kube-prometheus-stack`
- Loki using `loki-stack`
