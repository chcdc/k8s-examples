
## K8S Examples and Kubectl commands


## Kubectl commands


### kubectl get 

Use get to pull a list of resources you have currently on your cluster. 

- Pod
- Namespace
- Node
- Deployment
- Service
- ReplicaSets


### kubectl create
Now that we've gathered some resources, let's create some more. With kubectl, you can create nearly any type of resource in a cluster. Some of these resources do require configuration files and namespaces to set the resource to, as well as names. Resources you can create include:


- namespace (ns)
- cronjob
- deployment
- job
- service


### kubectl apply
Kubectl apply manages applications through files defining Kubernetes resources. It creates and updates resources in a cluster through running kubectl apply. This is the recommended way of managing Kubernetes applications on production. 
[docs](https://kubernetes.io/pt-br/docs/reference/kubectl/cheatsheet/#kubectl-apply)


