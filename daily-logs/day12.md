🚀 Day 12/15 – DevOps Sprint: Helm Deep Dive + Real-World Chart Deployment
✅ What I Did Today:
🔹 🧠 Learned Helm Internals:
Understood the Helm architecture (Client + Tiller concept in older versions, now client-only).
Grasped the difference between Helm Charts, Releases, Templates, and Repositories.
Explored the file structure: Chart.yaml, values.yaml, templates/, and charts/.

🔹 📦 Installed and Used Helm:
Installed Helm on my local machine and connected it to my EKS cluster.
Added a public Helm chart repo:
--helm repo add bitnami https://lnkd.in/g92VFZ3e
--helm repo update
🔹 🚀 Deployed Sample App with Helm:
Deployed Bitnami NGINX to EKS using Helm:
--helm install my-nginx bitnami/nginx
Verified service, rollout, and logs via kubectl.

🔹 ⚙️ Customized with values.yaml:
Modified the default configuration
service:
 type: LoadBalancer
replicaCount: 2
Upgraded the release with:
--helm upgrade my-nginx bitnami/nginx -f custom-values.yaml

🔹 🔄 Helm Lifecycle Operations:
Learned how to:
List installed charts: helm list
Rollback to previous release: helm rollback my-nginx 1
Delete chart: helm uninstall my-nginx

🧩 What I Understood:
Helm helps manage Kubernetes applications as packages.
Makes upgrades, rollbacks, and config changes easier in GitOps + CI/CD pipelines.
Using values.yaml with dynamic placeholders helps scale app configurations.

🚧 Challenges:
Understanding how templating ({{ .Values }}) works inside Helm was tricky at first.
Troubleshooted a LoadBalancer IP issue due to missing EKS permissions.
