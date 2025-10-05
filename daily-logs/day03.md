Day 3 Recap: EKS Mastery Begins

##Topic: AWS EKS + eksctl + kubectl + NodeGroup Essentials
Today, I deep-dived into Amazon EKS (Elastic Kubernetes Service)—the managed K8s service by AWS. Here’s what I accomplished:
What I Learned:
1.What is EKS and how it simplifies K8s management on AWS.
2.Installed and configured eksctl to provision EKS clusters easily using YAML definitions or CLI.
3. Understood the role of Node Groups and how they provide EC2 worker nodes for the cluster.
4. Set up and verified kubectl to interact with my EKS cluster.
5.Explored IAM roles, security groups, and VPC networking for EKS.

Successfully created a sample EKS Cluster using:
--eksctl create cluster --name devops-cluster --region ap-south-1 --nodes 2

Key Tools:
🔹 eksctl — Simplified EKS provisioning
🔹 kubectl — Cluster management
🔹 AWS CLI — Authentication & setup

##Learned how to attach IAM roles with least privilege for better security.
Setup kubectl config using:
aws eks --region ap-south-1 update-kubeconfig --name devops-cluster

Verified cluster health and node status using:
--kubectl get node

 From spinning up clusters to configuring CLI tools, today was a solid step toward mastering cloud-native DevOps. The power of infrastructure-as-code with eksctl makes K8s deployment feel like magic.
