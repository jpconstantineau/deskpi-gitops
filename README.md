# deskpi-gitops
My K3S Cluster Apps Managed Declaratively


## Prerequisites

- K3S Cluster is installed and up and running
- ArgoCD is installed as per standard installation steps

'''
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
'''

