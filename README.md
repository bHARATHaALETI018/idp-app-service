# idp-app-service

This repository contains a **developer-owned application** deployed using an
**Internal Developer Platform (IDP)** powered by **Argo CD and GitOps**.

Developers interact only with Git — no direct Kubernetes access required.

## 🚀 How It Works

1. Developer pushes code or config changes
2. Argo CD detects changes via Git
3. Application is automatically deployed
4. Platform ensures consistency, security, and reliability

## 🧑‍💻 Developer Responsibilities

- Application code
- Kubernetes manifests or Helm values
- Environment-specific configuration

## 🏗️ Platform Responsibilities

- Cluster management
- Argo CD configuration
- Security, RBAC, and policies
- Observability and networking

## 🔁 Deployment Model

- Git is the single source of truth
- No manual kubectl or Helm commands
- Rollbacks are done via Git revert

---

This is a sub-repo of the main one: [Internal-Developer-Platform](https://github.com/bHARATHaALETI018/internal-developer-platform.git)