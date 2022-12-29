kubectl create -f nginx-rs.yaml

kubectl get pods

kubectl get po -l tier=frontend

kubectl get rs nginx-rs -o wide

kubectl describe rs nginx-rs

Shutdown down

kubeclt get po -o wide

shutdown 1 node

kubectl get nodes

kubectl get po -o wide

Scaling up

kubectl scale rs nginx-rs --replicas=5

kubectl get rs nginx-rs

kubectl get po -o wide

clean up

kubeclt delete -f nginx-rs.yaml

kubectl get po -l app=nginx-app
