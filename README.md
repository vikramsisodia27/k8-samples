# k8-samples

Kubernetes can have multiple containers with in same POD but not of same kind.

# create a Pod
kubectl create -f pod-definition.yml

# get the list of Pod
kubectl get pods

# describe the Pod
kubectl describe pod myapp-pod

Replication controller run multiple instances of single Pod, Replication controller replaced with replica set







