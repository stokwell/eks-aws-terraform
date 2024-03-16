# AWS EKS Cluster with Terraform

(Terraform EKS Cluster Creation)[https://www.youtube.com/playlist?list=PLiMWaCMwGJXkeBzos8QuUxiYT6j8JYGE5]

```bash
aws eks --region eu-central-1 update-kubeconfig --name eks --profile terraform
```

```bash
kubectl apply -f /Users/stokwell/Projects/elixir/eks-aws-terraform/k8s/app.yml
```

## Next Steps 

### Manage k8s RBAC roles and AWS IAM polices 

(EKS Add User VS. Role: How to Add IAM User and IAM Role to AWS EKS Cluster?)[https://www.youtube.com/watch?v=aIpHYYcR7oU&list=PLiMWaCMwGJXkeBzos8QuUxiYT6j8JYGE5&index=7]  (Anton Putra YouTube)

Notes:

```bash
kubectl apply -f /Users/stokwell/Projects/elixir/eks-aws-terraform/k8s/rbac.yml
```

### Proper manage Terraform state

(How to manage Terraform State?)[https://www.youtube.com/watch?v=GgQE85Aq2z4] (Anton Putra YouTube)

### Confugure GitOps CD with ArgoCD

(ArgoCD Tutorial for Beginners | GitOps CD for Kubernetes)[https://www.youtube.com/watch?v=MeU5_k9ssrs] (TechWorld with Nana YouTube Channel)

(ArgoCD Tutorial for Beginners: GitOps CD for Kubernetes)[https://www.youtube.com/watch?v=zGndgdGa1Tc] (Anton Putra YouTube)