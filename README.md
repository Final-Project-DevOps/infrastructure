# KnowHub DevOps Infrastructure

![Docker](https://img.shields.io/badge/Docker-Containerization-blue)
![Docker Swarm](https://img.shields.io/badge/Docker-Swarm-blue)
![Prometheus](https://img.shields.io/badge/Monitoring-Prometheus-orange)
![Grafana](https://img.shields.io/badge/Dashboard-Grafana-yellow)
![CI/CD](https://img.shields.io/badge/Pipeline-GitHub_Actions-black)

Infrastructure configuration for KnowHub, a community knowledge-sharing platform implemented with DevOps practices.

## Overview

This repository contains deployment and operational configuration including:

- Docker containerization
- Docker Swarm orchestration
- CI/CD deployment workflow
- Configuration and secret management
- Monitoring infrastructure


## Architecture

Components:

- Frontend: React application
- Backend: Node.js / TypeScript REST API
- Database: PostgreSQL
- Monitoring: Prometheus + Grafana


## Deployment Stack

Infrastructure:

- Docker
- Docker Swarm
- GitHub Container Registry
- GitHub Actions
- Prometheus
- Grafana


## Network

Application services communicate through custom overlay network:

internal-net


## Monitoring

Prometheus collects metrics from node-exporter.

Grafana provides visualization dashboard.


## Security

Sensitive configuration is managed using Docker Secrets.

No credentials are stored directly inside configuration files.
