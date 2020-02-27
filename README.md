## Ansible Playbooks to bootstrap Kubernetes HA cluster

**Ansible Playbooks**: Configuring system and bootstap HA cluster
Palybooks includes: 

- 01-os-setup: Configuring System 
- 02-environment-setup: Installing runtime environments
- 03-load-balancer-setup: Installing HA load-balancer
- 04-etcd-cluster-setup: Initialize etcd cluster
- 05-control-plane-setup: Initialize control plane
- 06-glusterfs-setup: Initialize glusterfs cluster

## Usage

1) Make proper changes in files (changes that should be made are commented in files)
2) Run each playbook one by one and by order
3) You can install nginx-ingress controller with simple "kubectl apply -f nginx/" (You should create secret for nginx-ingress-controller)