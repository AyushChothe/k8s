# Kubernetes Playground

## Create Cluster

- Install [K3D](https://k3d.io)
- `k3d cluster create ash-cluster -p "30001-30005:30001-30005@loadbalancer" --servers 1 --agents 4 --kubeconfig-update-default`

## Dashboard Setup

- [K8S Dashboard Repo](https://github.com/kubernetes/dashboard)
- [K3S Dashboard Setup](https://docs.k3s.io/installation/kube-dashboard)
