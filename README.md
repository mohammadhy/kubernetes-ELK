# kubernetes-ELK
This is kubernetes manifests to run ELK + kafka 
we define namespace stack-elk and assign all deployment to this namespace and our elasticsearch and kibana has network type NodePort.
HOW IT WORKS:
## before run any deployment be sure your cluster available
### first run this deployment because our namespace create in this deployment you can remove it from file and run in command line like  ==> kubectl create namespace stack-elk


kubectl apply -f deployment-filebeat.yaml

