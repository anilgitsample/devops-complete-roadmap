# Kubernetes — Beginner to Advanced

## 🟩 BEGINNER LEVEL
### 1. Basics
- What is Kubernetes?
- Master vs Worker nodes
- Control Plane Components:
  - API server
  - Scheduler
  - Controller Manager
  - etcd

### 2. Core Objects
- Pods  
- ReplicaSets  
- Deployments  
- Services (ClusterIP, NodePort, LoadBalancer)

### 3. YAML Manifests
- apiVersion  
- kind  
- metadata  
- spec  

### 4. kubectl Basics
- kubectl get  
- kubectl describe  
- kubectl logs  
- kubectl exec  

---

## 🟨 INTERMEDIATE LEVEL
### 5. Config Management
- ConfigMaps  
- Secrets  
- Environment variables  

### 6. Networking
- CNI  
- kube-proxy  
- Cluster DNS  

### 7. Scaling
- HPA (Horizontal Pod Autoscaler)  
- VPA  
- Cluster Autoscaler  

### 8. Ingress
- Ingress controller  
- NGINX ingress  

### 9. Storage
- PV  
- PVC  
- StorageClass  

### 10. Helm
- Charts  
- Values  
- Releases  

---

## 🟥 ADVANCED LEVEL
### 11. Advanced Scheduling
- Affinity / Anti-affinity  
- NodeSelector  
- Taints & tolerations  

### 12. StatefulSets
- For databases  
- Headless services  

### 13. Operators
- CRDs  
- Operator pattern  

### 14. Security
- RBAC  
- Network Policies  
- Pod Security Policies (PSP deprecated → PSS)

### 15. Kubernetes in Cloud
- EKS  
- IAM Roles for Service Accounts (IRSA)  
- Load balancer controller  
- ECR integration  

---

## ✔ PRACTICE
- Deploy Nginx using Deployment + Service  
- Setup HPA  
- Create Ingress route  
- Deploy app through Helm  
