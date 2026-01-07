# 🚀 Zero-Downtime Deployment & Monitoring Showcase

![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fdnhngrt.github.io%2Fzero-downtime-pipeline&style=flat-square&label=Live%20Demo)
![Tech Stack](https://img.shields.io/badge/Stack-Docker%20%7C%20K8s%20%7C%20Prometheus-blue?style=flat-square)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

> **Note:** This repository hosts the **interactive case study presentation** (Static Web) demonstrating a DevOps architecture transformation.

## 🔗 Live Demo
View the interactive case study here:  
👉 **https://dnhngrt.github.io/zero-downtime-pipeline/**

---

## 📖 Project Overview

This project serves as a comprehensive **Engineering Case Study** detailing the migration of a legacy, manual deployment process into a modern, automated **DevOps Architecture**.

The goal was to solve critical stability issues in a SaaS environment, focusing on eliminating downtime during updates and establishing real-time observability.

### 🛑 The Problem (Situation)
Before implementation, the infrastructure suffered from:
*   **Manual Deployments:** Prone to human error and script failures.
*   **High Downtime:** Services went down for ~45 minutes during updates.
*   **Blind Spots:** No monitoring tools; crashes were reported by users, not systems.

### 🛠️ The Solution (Architecture)
I designed and implemented a **Zero-Downtime Pipeline** using the following stack:

| Component | Technology | Role |
| :--- | :--- | :--- |
| **CI/CD** | GitHub Actions | Automated testing, building, and deployment triggers. |
| **Containerization** | Docker | Ensuring environment consistency across Dev/Prod. |
| **Orchestration** | Docker Swarm / K8s | Managing container lifecycle and scaling. |
| **Proxy/Load Balancer** | Nginx | Handling Blue-Green deployment traffic switching. |
| **Observability** | Prometheus + Grafana | Scrapping metrics and visualizing system health. |

---

## 📊 Key Results & Impact

By shifting to Infrastructure as Code (IaC) and automation, the system achieved:

*   ✅ **99.99% Uptime:** Achieved through Blue-Green deployment strategy.
*   ✅ **15-Minute Release Cycle:** Reduced from 2 hours (87% improvement).
*   ✅ **Zero-Touch Recovery:** Automated rollbacks in case of health check failures.
*   ✅ **Full Visibility:** Real-time dashboards for CPU, Memory, and Request Latency.

---

## 📬 Contact

If you have questions about the architecture or want to discuss DevOps opportunities:

*   **Email:** alensana21@gmail.com
*   **Portfolio:** alensana.site


