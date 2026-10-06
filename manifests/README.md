# Kubernetes Helpers Manifests

This project contains simple Kubernetes manifest examples for common cluster behaviors and security patterns.

## Folder overview

- [02 - Toleration](02%20-%20Toleration) – shows how a pod can tolerate a taint so it can run on a tainted node.
- [03 - Sidecar](03%20-%20Sidecar) – demonstrates a deployment with an init container that runs before the main app container.
- [04 - Persistant Volume](04%20-%20Persistant%20Volume) – creates a persistent volume using a hostPath for local storage.
- [06 - Network Policy](06%20-%20Network%20Policy) – restricts ingress traffic based on namespace and pod labels.
- [07 - Quota](07%20-%20Quota) – applies resource limits to a namespace using a ResourceQuota.
- [08 - Static Pod](08%20-%20Static%20Pod) – shows a pod manifest meant to run as a static pod in kube-system.
- [10 - Roles](10%20-%20Roles) – demonstrates Kubernetes RBAC with a ServiceAccount and RoleBinding.
- [12 - Taint and toleration](12%20-%20Taint%20and%20toleration) – shows how taints restrict scheduling unless workloads tolerate them.

## General purpose

These manifests are intended as learning examples for:

- node scheduling control
- pod startup sequencing
- storage basics
- network isolation
- quota enforcement
- static pod placement
- RBAC and least privilege

Use each folder independently and apply its YAML to a Kubernetes cluster for testing and practice.
