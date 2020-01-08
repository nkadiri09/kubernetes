## Kubectl commands

    kubectl config get-contexts
    kubectl get pods

    aws eks update-kubeconfig --name opssuite-dev2-us-east-1
    kubectl get pods -n <name>


    //Kube config file: 
    vi ~/.kube/config

    //update Kubeconfig file with server
    aws eks update-kubeconfig --name opssuite-dev2-us-east-1

    Describe pods:
    kubectl describe pod <pod-name>
