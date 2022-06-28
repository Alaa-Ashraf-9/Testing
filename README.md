For Kubernetes Creation Part (One Master Node and Two Worker Nodes)
There are two methods (Manually on EC2 and EKS service)
for EC2 i followed the steps from the below two sites
https://upcloud.com/resources/tutorials/install-kubernetes-cluster-centos-8
and for kuberntes tools installation on ec2
https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/install-kubeadm/
--------------------------------------------------------------------------------------------
I made Specific role for EKS Matser Node and attached to it Restriction policy that allow my public ip to access master node
Ingress-nginx deployed
 bkimminich/juice-shop deployed 
 For Exposing App inside the cluster i used ClusterIP Service type
 For Exposing App outside the cluster i used ingress basic yaml file
