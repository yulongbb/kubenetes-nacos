# kubenetes with nacos


* **Clone Repository**


```shell
git clone https://github.com/yulongbb/kubenetes-nacos.git
```

## mysql startup

```shell
kubectl create -f mysql-local.yaml
```

## nacos startup

```shell
kubectl create -f nacos-no-pvc-ingress.yaml
```
