# Kubernetes(k8s) course

![image](https://user-images.githubusercontent.com/24622526/48015484-4456b800-e14f-11e8-876a-498cd73db5c1.png)


### 1. About k8s & its archetecture
    
    * etcd
    
    * kubectl
    
    * API Server
    
    * kubelet
    
    * kube-proxy
    
    * kube-scheduler
    
    * kube-controller-manager
    
    * node (master & worker)
    
    * pod
    
    * container runtime

### 2. Docker Swarm vs k8s.

### 3. nodes, pods, deployments, services, labels, replica sets, namespace, volume etc

### 4. Single-node cluster - minikube

    * Single-node cluster setup

    * Creating deployments
    
    * Creating services
    
    * Monitor (dashboard)

### 5. Multi-node cluster  - kubeadm/kops

    * provisioning the AWS EC2 instances
    
    * multi-node cluster setup
    
    * master and worker node

    * Creating/updating/removing/rollback deployments
    
        * deplloyments using yml files
    
    * Creating services.
    
    * Expose the deployment.
    
    * kubeadm comands
      
         * kubeadm version
         * kubeadm init
         * kubeadm join
         * kubeadm reset
         * kubeadm token
         * kubeadm config
    
    * kops commands
    
         * kops version
         * kops create
         * kops update
         * kops edit
         * kops get
         * kops validate
         * kops delete

### 6. kubectl commands & examples.

    * kubectl help    
    * kubectl cluster-info    
    * kubectl expose    
    * kubectl run    
    * kubectl expose    
    * kubectl plugin    
    * kubectl scale    
    * kubectl get   
    * kubectl dashboard    
    * kubectl describe    
    * kubectl create    
    * kubectl apply    
    * kubectl delete    
    * kubectl exec
    * kubectl cp
    * kubectl rollout    
    * kubectl proxy

### 7. Examples on Jenkins + Github + maven + nexus + docker + k8s.

    * Jenkins, git, maven, nexus, docker, k8s installation on AWS EC2 instance
    
    * Jenkins job setup as to 
    
         * checkout the code from Github
         
         * build/package using maven
         
         * build the docker file to create docker images
         
         * push the docker images to dockerhub
         
         * deploy the docker image to k8s.

