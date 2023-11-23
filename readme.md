KUBERNETES CLUSTER DEPLOYMENT USING VAGRANT AND ANSIBLE

1. Create three working machines for K8s cluster. Ansible configuration 
management included in the directory  will install kubeadm and configure 
them as  per requirments.

$ sudo vagrant up

2. Apply the kubernetes yaml files for dashboard

$ kubectl apply -f .




