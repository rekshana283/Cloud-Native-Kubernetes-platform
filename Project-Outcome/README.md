 ## Kubernetes Concepts Demonstrated

- Kubernetes Deployments
- Kubernetes Pods
- ReplicaSets
- Services
- NodePort
- Scaling
- Self-Healing
- Rolling Updates
- ConfigMaps
- Secrets
- Resource Requests and Limits
- Liveness Probes
- Readiness Probes
- Ingress
- Logging
- Troubleshooting
- ImagePullBackOff
- Rollout History
- Rollback
- Metrics Server
- CPU and Memory Monitoring
- Horizontal Pod Autoscaler
- Automatic Scale-Up
- Automatic Scale-Down
- Kubernetes Namespaces
- Namespace Isolation
- Kubernetes Dashboard

---

## Project Highlights

### Application Management

- Deployed NGINX using Kubernetes
- Exposed the application using a NodePort Service
- Scaled workloads using Kubernetes replicas
- Verified Kubernetes self-healing behaviour

### Application Reliability

- Configured liveness and readiness probes
- Performed rolling updates
- Tested deployment failures
- Investigated ImagePullBackOff
- Performed safe rollback operations

### Kubernetes Monitoring

- Enabled Metrics Server
- Monitored node and pod resource usage
- Configured Horizontal Pod Autoscaler
- Demonstrated automatic scale-up and scale-down

### Kubernetes Organization

- Created a dedicated `dev` namespace
- Deployed workloads inside the namespace
- Verified namespace separation
- Used Kubernetes Dashboard for visual workload inspection

---

## Project Outcome

This project provided hands-on experience with the complete lifecycle of a containerized application running on Kubernetes.

The project covered:

**Deployment → Networking → Scaling → Self-Healing → Configuration → Health Monitoring → Logging → Troubleshooting → Rollouts → Rollback → Resource Monitoring → Auto Scaling → Namespaces → Dashboard**

The final implementation was completed locally using Minikube without requiring paid cloud infrastructure.

---

## Repository Structure

```text
Cloud Native Kubernetes Platform
│
├── README.md
│
├── Kubernetes
│   ├── 01-Environment-and-Kubernetes-Setup.md
│   ├── 02-NGINX-Deployment.md
│   ├── 03-Kubernetes-Service.md
│   ├── 04-Scaling-and-Self-Healing.md
│   ├── 05-Kubernetes-Service-Details.md
│   ├── 06-Kubernetes-Rolling-Update.md
│   ├── 07-ConfigMap-Secret-and-Resources.md
│   ├── 08-Kubernetes-Health-Probes.md
│   ├── 09-Kubernetes-Ingress.md
│   ├── 10-Kubernetes-Logging.md
│   ├── 11-Kubernetes-Troubleshooting.md
│   ├── 12-Kubernetes-Rollout-History.md
│   ├── 13-Kubernetes-Rollback.md
│   ├── 14-Kubernetes-Final-Health-Check.md
│   └── 15-Metrics-Server-and-HPA.md
│
└── Screenshots
    ├── 01-docker-version.png
    ├── 02-docker-info.png
    ├── ...
    ├── 21-kubernetes-final-health-check.png
    ├── 22-metrics-server-readiness-issue.png
    ├── 23-metrics-server-logs.png
    ├── 24-kubernetes-node-metrics.png
    ├── 25-kubernetes-hpa-auto-scaling.png
    ├── 26-kubernetes-hpa-scale-down.png
    ├── 27-kubernetes-namespace-deployment.png
    ├── 28-kubernetes-namespace-isolation.png
    ├── 29-kubernetes-dashboard-workloads.png
    └── 30-kubernetes-dashboard-pods-replicas.png
