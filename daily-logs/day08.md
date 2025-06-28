🛡️ Day 9/15 - DevOps Challenge
🔐 Topic: Securing ArgoCD & Managing Secrets with Sealed Secrets

Today I explored how to secure ArgoCD and implement Kubernetes-friendly secrets management using Sealed Secrets by Bitnami.

🔍 What I achieved:

Enabled HTTPS access for ArgoCD using port-forwarding and secret management

Configured RBAC in ArgoCD for fine-grained access control

Installed Sealed Secrets controller in the cluster

Encrypted Kubernetes secrets using kubeseal CLI

Committed sealed secrets safely into Git (no plain-text!)

Verified decryption and application by ArgoCD on sync

💡 Key Learning:
In a GitOps workflow, handling secrets securely is critical. Sealed Secrets allows me to store encrypted secrets in Git while ensuring ArgoCD decrypts and applies them securely in the cluster.

🛠️ Tools Used:
ArgoCD, Sealed Secrets, kubectl, kubeseal, GitHub, AWS EKS, Kubernetes
