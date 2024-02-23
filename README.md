# k8-samples

Kubernetes can have multiple containers with in same POD but not of same kind.

Replication controller run multiple instances of single Pod, Replication controller replaced with replica set

Deployment provide capability to update underlying instance, rolling update, undo change, pause and resume changes

# create a Pod
kubectl create -f pod-definition.yml

# get the list of Pod
kubectl get pods

# describe the Pod
kubectl describe pod myapp-pod

# get deployments
kubectl get deployments
kubectl get replicaset
kubectl get pods

# get all objects
kubectl get all







