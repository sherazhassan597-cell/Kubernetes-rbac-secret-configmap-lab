# Kubernetes-rbac-secret-configmap-lab
## Project Overview 
This project demonstrates implementation of Kubernetes RBAC, Secrets and ConfigMaps in a lab environment. 
## What I Implemented 
- Created custom Namespace
- Created ClusterRole with permissions
- Bound ClusterRole using ClusterRoleBinding
- Created Secret using Base64 encoding
- Craeted ConfigMap for application configuration
- Verified access using kubectl commands
  ## Commands Used
  kubectl create -n dev-ops-team
  kubectl create clusterrole cluster-497
  kubectl create clusterrolebinding cluster-1
  kubectl create secret secret secret-2
  kubectl apply -f configmap.yaml
  echo -n "pakistani1234" | base64
  ## Key Concepts
  RBAC ensures secure access control.
  Secret store senstive data securely.
  ConfigMaps manage nonsenstive configuration.
  ## Files Used
  commands.txt comfigmap.yaml 
  
