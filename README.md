# multus

### Install multus-cni
```bash
git clone https://github.com/k8snetworkplumbingwg/multus-cni
cd multus-cni
cat ./deployments/multus-daemonset-thick-plugin.yml | kubectl apply -f -
```

### Verify installation
```bash
kubectl get pods -A
```
