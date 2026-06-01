# GitOps repository for ArgoCD

This repository contains ArgoCD Application manifests, Projects, ApplicationSets, and raw manifests.

## Structure

- `bootstrap/` – root App-of-Apps
- `apps/` – individual Application manifests
- `appsets/` – ApplicationSet definitions
- `values/` – Helm values for podinfo (dev/prod)
- `projects/` – ArgoCD AppProject definitions
- `manifests/` – raw Kubernetes manifests (hello-world)
