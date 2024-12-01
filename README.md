# 2048 App Deployment Project

In this project, we deployed applications using EKS, provisioned using Terraform. Automated deployment using GitHub actions. Deployed real-time monitoring and visualisation with Prometheus and Grafana.

## Architecture diagram:

![alt text](architecturaldiagram.eks.png)

## Tech Stack:
 
- **Kubernetes:** Orchestrates our containerised workloads for scalability and reliability.
- **ArgoCD:** Implementing GitOps for automated and declarative continuous delivery.
- **Prometheus:** Collects and queries app and infrastructure metrics for monitoring.
- **Grafana:** Visualises metrics and provides actionable insights through customised dashboards.
- **Docker:** Containerises the 2048 app to ensure a consistent runtime environment.