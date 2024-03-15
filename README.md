(Terraform EKS Cluster Creation)[https://www.youtube.com/playlist?list=PLiMWaCMwGJXkeBzos8QuUxiYT6j8JYGE5]

aws eks --region eu-central-1 update-kubeconfig --name eks --profile terraform

kubectl apply -f /Users/stokwell/Projects/elixir/eks-aws-terraform/k8s/app.yml

## Last Steps 

kubectl apply -f /Users/stokwell/Projects/elixir/eks-aws-terraform/k8s/rbac.yml

(EKS Add User VS. Role: How to Add IAM User and IAM Role to AWS EKS Cluster?)[https://www.youtube.com/watch?v=aIpHYYcR7oU&list=PLiMWaCMwGJXkeBzos8QuUxiYT6j8JYGE5&index=7]