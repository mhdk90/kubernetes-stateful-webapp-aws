# Kubernetes-Based Web Application on AWS

## Overview
This project demonstrates a Kubernetes-based web application on AWS using WordPress, MySQL, persistent storage, and a cloud load balancer.

## Goal
Build a containerized web application stack with Kubernetes resources for deployment, networking, and storage.

## Current Scope
- Namespace
- Secret for database credentials
- MySQL Deployment and Service
- WordPress Deployment and Service
- PersistentVolumeClaims for data persistence
- External access with LoadBalancer Service

## Repository Structure
- `k8s/` – Kubernetes manifests
- `docs/` – notes and architecture explanations

## Planned Next Steps
- Split the manifest into separate files
- Add architecture diagram
- Add EBS-backed and EFS-backed storage notes
- Add Ingress and TLS
- Add deployment notes for AWS

## Security Notes
- No production credentials are stored in this repository
- Secrets should be created securely at deploy time
- Environment-specific settings should be adjusted before deployment

## What I Learned
- How to define Kubernetes workloads in YAML
- How to expose an application with a LoadBalancer Service
- How to use PersistentVolumeClaims for storage
- How to present Kubernetes projects professionally on GitHub
