# k8s foreword
Kubernetes (K8s) is an open-source platform designed to automate the deployment, scaling, and operation of application containers.

- Kubernetes offers functionalities similar to those found in Spring Cloud, such as:
- Service registration and discovery
- API gateway
- Self-healing mechanisms
- Load balancing
- Configuration management

However, Spring Cloud requires the use of Java for development, which limits the environment and programming languages that can be used. Kubernetes, on the other hand, does not have these restrictions, allowing for greater flexibility across various environments and languages. We can thank Google for this advancement in technology!"

# K8s main points

There are two points in kubernetes platform as below:
   - control plane
     1. kube-apiserver (role : operation department)(commuicate with woker node)
     2. kube-scheduler (role : VP ) (create node ,cpu resource , memory and check the node 's status)
     3. kube-controller-manager (role:CEO) (run cluster including node controller , job   controller , 
                          endpoints controller , service account &　Token Controllers)
     4. etcd (role:secretary) (a key table which is using to save the configuration and cluster status .)
  
   - woker node
     1. kubelet (branch manager) (access the node and set the node)
     2. kube-proxy (connector) (network agent)
     3. container runtime
        - pod
        - containers

# minikube
  - must run below cmd to use containerd because minikube is installing kubernetes V1.25.0 or later version that give up docker and change to containerd. (minikube start --container-runtime=containerd or  minikube start --container- 
    runtime=containerd --no-vtx-check)
  - can use kubectl to connect apiserver that we can control all nodes.
# K3S 
Before try to set a K8S platform , this project try to use K3S as the attempt first .



# remarks
k8s is not needed docker after verion 1.24 or later 
  




