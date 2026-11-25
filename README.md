# Kubernetes Learning Journey

This repository tracks my progress, notes, YAML manifests, and hands-on labs while learning Kubernetes (K8s).

## Repository Structure

```text
.
├── 01-basics/                  # Architecture, cluster setup, and core concepts
├── 02-workloads/               # Pods, ReplicaSets, Deployments, Jobs
├── 03-networking/              # Services, DNS, Ingress, NetworkPolicies
├── 04-config-and-storage/      # ConfigMaps, Secrets, Volumes, PV/PVC
├── 05-projects/                # Hands-on mini-projects and practice labs
├── notes/                      # Daily learning log and kubectl cheatsheet
├── Kubernetes K8s Notes.pdf    # Reference notes PDF
├── .gitignore
└── README.md
```

## Learning Roadmap & Progress

- [ ] **01. Basics**: Kubernetes architecture (Control Plane, Worker Nodes), `kubectl`, Minikube / Kind
- [ ] **02. Workloads**: Pods, Labels & Selectors, ReplicaSets, Deployments, Rollouts
- [ ] **03. Networking**: Services (`ClusterIP`, `NodePort`, `LoadBalancer`), CoreDNS, Ingress
- [ ] **04. Config & Storage**: `ConfigMap`, `Secret`, `emptyDir`, `PersistentVolume`, `PersistentVolumeClaim`
- [ ] **05. Projects**: Deploy a multi-tier app and practice troubleshooting

## Quick Links

- [Learning Log](notes/learning-log.md)
- [kubectl Cheatsheet](notes/kubectl-cheatsheet.md)
