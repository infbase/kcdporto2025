# From Cloud Bills to GitOps: Our FinOps Journey with Kubernetes

KCD Porto 2025 Talk by Filipe Revez and Nuno Guedes

## Overview

This repository contains the GitOps configuration and custom applications for our demo showcasing FinOps practices with Kubernetes.

## Tech Stack

- **AKS Cluster**: Azure Kubernetes Service
- **ArgoCD**: GitOps continuous delivery
- **OpenCost**: Kubernetes cost monitoring
- **Kyverno**: Policy management and governance
- **cert-manager**: Automated TLS certificate management
- **Grafana**: Azure Managed (visualization)
- **Prometheus**: Azure Managed (metrics)

## Domain

**Primary Domain**: `finops.kcdporto.pt`

Services:
- ArgoCD: `https://argocd.finops.kcdporto.pt`
- OpenCost: `https://opencost.finops.kcdporto.pt`

## Repository Structure

```
.
├── argocd/
│   ├── install/              # ArgoCD installation manifests
│   └── applications/         # ArgoCD Application definitions
├── components/
│   ├── opencost/            # OpenCost installation
│   ├── kyverno/             # Kyverno policies and installation
│   ├── cert-manager/        # Certificate management
│   ├── ingress/             # Ingress resources
│   └── custom-apps/         # Custom demo applications
```