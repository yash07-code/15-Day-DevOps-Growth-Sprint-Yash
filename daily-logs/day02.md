#  Day 2 – ArgoCD + GitOps Fundamentals

### What I Did:
- Understood the GitOps philosophy
- Installed ArgoCD on Kubernetes cluster
- Learned ArgoCD architecture:
  - API Server
  - Repo Server
  - Application Controller
- Created `Application` YAML to deploy a test app
- Learned ArgoCD sync strategies: auto-sync, manual sync
- Explored rollback and health check mechanisms
- Used ArgoCD Web UI and CLI to sync deployments from Git

### Key Takeaways:
- Git is the single source of truth for K8s deployments
- ArgoCD makes rollbacks & syncs effortless and observable
- You deploy infrastructure just by pushing to Git — that’s powerful

### Next Up:
→ Jenkins → DockerHub → ArgoCD → EKS  
→ Full GitOps CI/CD pipeline in action
