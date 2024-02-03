
#Configure K9s kubernetes context to connect to K3s Cluster. 
cat /etc/rancher/k3s/k3s.yaml
export KUBECONFIG=/etc/rancher/k3s/k3s.yaml
kubectl get pods --all-namespaces
k9s --kubeconfig /etc/rancher/k3s/k3s.yaml



