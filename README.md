# 1click-kubernetes
**Welcome to 1ckick Kubernetes World** , Lets take a sneek peak on how we can install Kubernetes multi-master cluster using Ansible .


<img width="36" alt="kube" src="https://user-images.githubusercontent.com/99710234/154669206-f2927d33-db97-43ac-b8e5-1340692767d6.png"> <img width="37" alt="docker" src="https://user-images.githubusercontent.com/99710234/154669208-eeab2758-d86d-438b-a566-071690820a6a.png"> <img width="109" alt="flannel" src="https://user-images.githubusercontent.com/99710234/154669213-e7153a7e-14b8-4959-8761-9a300348f074.png">

______________________________________________________________________________________________

**Pre-Requesties**

Ubuntu Server image 18.04 for master and worker nodes .
https://mirror.ette.biz/ubuntu-releases/18.04.6/ubuntu-18.04.6-live-server-amd64.iso

**We are building the Kubernetes cluster on basis of following compeonents**

1) Ubuntu server 18.04 LTS Versions 
2) Containerd as runtime
3) Kubernetes orchestration of course :)
4) Kubernetes Dashboard
5) Flanneld for Networking
6) calico for network policy management 
7) Prometheus Monitoring
8) Grafana for Metrics

**Installation Steps **
* Get your vm's ready with unique ip and set hostnames as specified (or as your wish) .
  kubemaster1
  kubemaster2
  kubeslave1
  kubeslave2
  
 * You need to be able to SSH into each of these nodes as root using the SSH key pair login .
 * 
 
  



 
