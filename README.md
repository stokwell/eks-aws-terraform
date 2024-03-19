# AWS EKS Cluster with Terraform

(Typical AWS Network Architecture in one diagram)[https://blog.bytebytego.com/i/142629473/one-picture-is-worth-a-thousand-words-typical-aws-network-architecture-in-one-diagram] (ByteByteGo Newsletter)

(Terraform EKS Cluster Creation)[https://www.youtube.com/playlist?list=PLiMWaCMwGJXkeBzos8QuUxiYT6j8JYGE5] (Anton Putra YouTube Playlist)

```bash
aws eks --region eu-central-1 update-kubeconfig --name eks --profile terraform
```

```bash
kubectl apply -f /path_to_project/eks-aws-terraform/k8s/app.yml
```

## Next Steps 

### Manage k8s RBAC roles and AWS IAM polices 

(EKS Add User VS. Role: How to Add IAM User and IAM Role to AWS EKS Cluster?)[https://www.youtube.com/watch?v=aIpHYYcR7oU&list=PLiMWaCMwGJXkeBzos8QuUxiYT6j8JYGE5&index=7]  (Anton Putra YouTube)

Notes:

```bash
kubectl apply -f /path_to_project/eks-aws-terraform/k8s/rbac.yml
```

### Proper manage Terraform state

(How to manage Terraform State?)[https://www.youtube.com/watch?v=GgQE85Aq2z4] (Anton Putra YouTube)

## CI/CD Research

### Gitlab CI/CD

Урок 21: CI/CD. Часть 1. Вечерняя школа «Kubernetes для разработчиков» [https://www.youtube.com/watch?v=7rZgXQmBeso]

### Werf

werf — наш инструмент для CI/CD в Kubernetes (Дмитрий Столяров, Флант, DevOpsConf 2019) [https://www.youtube.com/watch?v=cK3ackGUTLw]

Werf: Glue Together Git, Docker, Helm, Kubernetes For CI/CD Pipelines [https://www.youtube.com/watch?v=WM06S_ltcVs]

###  GitOps CD with ArgoCD

(ArgoCD Tutorial for Beginners | GitOps CD for Kubernetes)[https://www.youtube.com/watch?v=MeU5_k9ssrs] (TechWorld with Nana YouTube Channel)

(ArgoCD Tutorial for Beginners: GitOps CD for Kubernetes)[https://www.youtube.com/watch?v=zGndgdGa1Tc] (Anton Putra YouTube)

(ArgoCD Image Updater: Decouple CI from CD! #2)[https://www.youtube.com/watch?v=cTQybeDzngU] (Anton Putra YouTube)

## Security

TBD