# homelab
HomeLab setup with Kubernetes

# Install MicroK8s latest version
snap install microk8s --channel=latest/edge/strict

# Start MicroK8s
sudo microk8s start
Verify -> sudo microk8s status --wait-ready

# Enable necessary addons
sudo microk8s enable dns 
microk8s enable dashboard
microk8s enable storage


