# DevOps Kubernetes Homeworks 

This repository contains Kubernetes-based homework assignments (Homework 7–10) from my DevOps course. Each folder represents a different challenge focused on deploying and managing containerized applications in a Kubernetes cluster.

---

##  Homework Overview

### 🟨 Homework 7 – Simple Deployment and Service
- Deployed a basic app using `Deployment`
- Exposed it using a `NodePort` service

### 🟩 Homework 8 – Ingress with Two Versions
- Deployed two versions of an app
- Configured `Ingress` with:
  - Host-based routing (e.g. `ver1.example.com`)
  - Path-based routing (`/v1`, `/v2`)
- Used `Traefik` as the Ingress Controller

### 🟦 Homework 9 – Versioned App + Ingress
- Deployed and exposed two app versions
- Extended Ingress with more robust routing rules
- Used custom domain mappings via `/etc/hosts`

### 🟥 Homework 10 – EMQX Cluster
- Deployed a 3-node EMQX (MQTT broker) cluster using:
  - `StatefulSet` for stable pod identities
  - `Headless Service` for DNS-based discovery
  - `ConfigMap` and `Secret` for cluster config
  - Persistent storage for `/opt/emqx/data`
- Verified cluster with `emqx_ctl cluster status`
- Manually joined nodes to complete the cluster

---

##  Tools Used
- Kubernetes (`kubectl`, YAML)
- Docker Desktop / K3d
- EMQX MQTT Broker
- Traefik Ingress
- GitHub for version control

---
