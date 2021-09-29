# ETCD for Beginners

### What is ETCD ?
It is a distributed reliable key-value store that is secure 

### ETCD Operate

```
./etcd
./etcdtl set key1 value1
./etcdtl get key1
```

### ETCD in Kubernetes
```
kubectl exec etcd-master -n kube-system etcdctl get / --prefix -keys-only
kubectl -n kube-system get po   
```