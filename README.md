k8s-1.17.0 test success version

fork from https://github.com/coreos/kube-prometheus


## Intall kube-prometheus
```shell
kubectl create -f manifests/setup

kubectl create -f manifests/
```
## Intall  custom-metrics
```
kubectl create -f  experimental/custom-metrics-api/
```
