# Kubernetes Service

## Overview

A Kubernetes Service was created to provide stable network access to the NGINX application.

The Service connects incoming traffic to the NGINX Pods managed by the Deployment. The NodePort type was used to make the application accessible through the Minikube environment.

## 1. Create the Kubernetes Service

The NGINX Deployment was exposed using a NodePort Service.

```bash
kubectl expose deployment nginx --type=NodePort --port=80
```

This creates a Service named `nginx` and exposes port `80` of the NGINX application.

## 2. Verify the Service

The Service was checked using:

```bash
kubectl get services
```

This command displays the available Kubernetes Services and their exposed ports.

## 3. Check Service Endpoints

The endpoints associated with the NGINX Service were verified using:

```bash
kubectl get endpoints nginx
```

This confirms that the Service has backend Pod endpoints available to receive traffic.

## 4. Inspect Service Details

Detailed information about the Service was viewed using:

```bash
kubectl describe service nginx
```

This provides information such as the Service type, ports, selector, endpoints, and other configuration details.

### Proof

![Kubernetes Service Details](../Screenshots/11-kubernetes-service-details.png)

## Result

The NGINX application was successfully exposed through a Kubernetes NodePort Service. The Service configuration and backend endpoints were verified successfully.
