Day 7 of My 30-Day DevOps Growth Sprint – IAM, Security, and EKS 🔐⚙️
Today, I focused on Identity and Access Management (IAM) within the AWS ecosystem — a foundational piece that ensures security and proper 
permissions when working with services like EKS, EC2, and S3.

🔍 What I learned:
1.IAM Users, Groups, Roles, and Policies in-depth
2.How IAM integrates with EKS via eksctl to attach OIDC provider and service roles
3.Fine-grained IAM policies to control access to Kubernetes nodes and workloads
4.Created and attached IAM roles for EKS Node Groups
5.Understood how IAM for Service Accounts (IRSA) works in Kubernetes

Hands-on Work:
--Created a new EKS cluster using eksctl with IAM roles
--Linked IAM role with Kubernetes service accounts for secure pod access
--Tested role-based access and validated secure communication between services
🔐 Security is not optional—it's baked into the DevOps culture. Today was all about enforcing the principle of least privilege and making sure my EKS workloads only get access to what they truly need.

🔗 Tools used: eksctl, AWS IAM, kubectl, AWS CLIhashtag#DevOps hashtag#AWS hashtag#EKS hashtag#IAM hashtag#Kubernetes hashtag#CloudSecurity hashtag#30DaysOfDevOps hashtag#LearningInPublic hashtag#DevOpsInternship hashtag#GitOps hashtag#CI_CD hashtag#HelmNext
