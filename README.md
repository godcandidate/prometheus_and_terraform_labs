# Prometheus and Terraform Labs

This repository contains hands-on labs and configurations for deploying **Prometheus**-based monitoring solutions alongside **Terraform**-managed infrastructure. The goal is to provide a practical learning experience for setting up monitoring systems and managing cloud resources using Infrastructure-as-Code (IaC) principles.

---

## **Overview**

The repository is divided into two main sections:

1. **Prometheus Monitoring Stack**:
   - Learn how to deploy a monitoring stack with **Prometheus**, **Grafana**, and **Node Exporter**.
   - Visualize system metrics and create interactive dashboards in Grafana.

2. **Terraform Infrastructure**:
   - Explore modular Terraform configurations to provision and manage AWS resources such as EC2 instances, VPCs, and EKS clusters.
   - Follow best practices for state management, security, and modularity.

---

## **What You'll Learn**

- How to set up a Prometheus-based monitoring stack for system metrics.
- How to use Terraform to automate the deployment of AWS infrastructure.
- Best practices for combining monitoring and infrastructure management in real-world scenarios.

---

## **Repository Structure**

```
├── prometheus/               # Prometheus + Grafana monitoring stack
│   ├── docker-compose.yml    # Docker Compose file for Prometheus, Grafana, and Node Exporter
│   ├── prometheus.yml        # Prometheus configuration file
│   └── grafana-dashboard.json # Example Grafana dashboard JSON
│
├── terraform/                # Terraform configurations for AWS infrastructure
│   ├── ec2-deployment/       # EC2 instance deployment with networking
│   ├── eks-deployment/       # EKS cluster deployment with worker nodes
│
└── README.md                 # Main documentation
```

---

## **Getting Started**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/prometheus_and_terraform_labs.git
   cd prometheus_and_terraform_labs
   ```

2. Choose a lab or project:
   - Navigate to the `prometheus/` directory for monitoring labs.
   - Navigate to the `terraform/` directory for infrastructure labs.

3. Follow the instructions in each folder's `README.md` for setup and usage.

---


