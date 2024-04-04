# k8s foreword
Kubernetes (K8s) is an open-source platform designed to automate the deployment, scaling, and operation of application containers.

Kubernetes offers functionalities similar to those found in Spring Cloud, such as:
Service registration and discovery
API gateway
Self-healing mechanisms
Load balancing
Configuration management

However, Spring Cloud requires the use of Java for development, which limits the environment and programming languages that can be used. Kubernetes, on the other hand, does not have these restrictions, allowing for greater flexibility across various environments and languages. We can thank Google for this advancement in technology!"

# K8s main points

There are two points in kubernetes platform as below:
control plane (role:headcounter)
  kube-apiserver (role : operation department)(commuicate with woker node)
  kube-scheduler (create node ,cpu resource , memory and check the node 's status)
  kube-controller-manager (role:CEO) (run cluster including node controller , job   controller , 
                          endpoints controller , service account &　Token Controllers)
  etcd (role:secretary) (a key table which is using to save the configuration and cluster status .
  
woker node
  kubelet (access the node and set the node)
  kube-proxy (network agent)
  container runtime
    pod
    containers
    
# K3S 
Before try to set a K8S platform , this project try to use K3S as the attempt first .

# minikube



# remarks
k8s is not needed docker after verion 1.24 or later 
  




