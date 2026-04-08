\# Kubernetes-Based Web Application on AWS



\## Overview

This project demonstrates a Kubernetes-based web application on AWS using WordPress, MySQL, persistent storage, and a cloud load balancer.



\## Goal

Build a containerized web application stack with Kubernetes resources for deployment, networking, and storage.



\## Current Scope

\- Namespace

\- Secret for database credentials

\- MySQL Deployment and Service

\- WordPress Deployment and Service

\- PersistentVolumeClaims for data persistence

\- External access with LoadBalancer Service



\## Files

\- `k8s/wordpress-mysql.yaml` – Kubernetes manifest for the application stack

\- `docs/` – Notes and architecture explanations



\## Services / Concepts Covered

\- Kubernetes Deployments

\- Kubernetes Services

\- PersistentVolumeClaims

\- WordPress

\- MySQL

\- AWS load balancing integration



\## Planned Next Steps

\- Add an architecture diagram

\- Split the manifest into separate files

\- Add EBS-backed and EFS-backed storage options

\- Add Ingress and TLS

\- Add deployment notes for AWS



\## What I Learned

\- How to define Kubernetes workloads in YAML

\- How to expose an application with a LoadBalancer Service

\- How to use persistent storage requests with Kubernetes

\- How to present Kubernetes projects professionally on GitHub

