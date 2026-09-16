## Kubernetes Namespaces and Dashboard

A separate `dev` namespace was created to demonstrate Kubernetes workload organization and namespace isolation.

An NGINX deployment was created inside the `dev` namespace and verified successfully.

### Namespace Deployment Proof

![Kubernetes Namespace Deployment](Screenshots/27-kubernetes-namespace-deployment.png)

The workloads in the `default` and `dev` namespaces were checked separately to demonstrate logical workload separation.

### Namespace Isolation Proof

![Kubernetes Namespace Isolation](Screenshots/28-kubernetes-namespace-isolation.png)

---

## Kubernetes Dashboard

The Minikube Kubernetes Dashboard addon was enabled to provide a visual interface for inspecting Kubernetes workloads and resources.

The Dashboard was opened locally and used to view the deployed workloads.

### Dashboard Workloads Proof

![Kubernetes Dashboard Workloads](Screenshots/29-kubernetes-dashboard-workloads.png)

The Dashboard was also used to inspect Pods and ReplicaSets associated with the Kubernetes deployment.

### Dashboard Pods and ReplicaSets Proof

![Kubernetes Dashboard Pods and ReplicaSets](Screenshots/30-kubernetes-dashboard-pods-replicas.png)

### Result

The project successfully demonstrated Kubernetes namespace organization, namespace isolation, and visual workload monitoring using the Kubernetes Dashboard.

---

## Project Status

**Completed**

 
