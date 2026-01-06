# devops-intern-final

# DevOps Intern Final Project

**Name:** Akki Mahesh  
**Date:** 2026-01-06  

![CI](https://github.com/akkimahesh/devops-intern-final/actions)

---

## 📌 Project Overview
This project demonstrates core DevOps fundamentals including Git, Linux scripting, Docker, CI/CD, Nomad deployment, and basic monitoring using Grafana Loki.

---

## 1. Git & GitHub
- Public repository with version control
- Sample Python script printing `Hello, DevOps!`

Run:
```bash
python hello.py

## 2. Linux & Scripting

- Shell script to show system info:

./scripts/sysinfo.sh


Outputs:

Current user

Date

Disk usage

## 3. Docker

Build and run container:

docker build -t hello-devops .
docker run hello-devops

## 4. CI/CD (GitHub Actions)

Pipeline runs hello.py on every push

Status badge added to README

## 5. Nomad Deployment

Run Docker container via Nomad:

nomad job run nomad/hello.nomad