# Pod Label Operator

It is basically the same operator like -> [https://kubernetes.io/blog/2021/06/21/writing-a-controller-for-pod-labels/](https://kubernetes.io/blog/2021/06/21/writing-a-controller-for-pod-labels/)

But this version of should work with the newer version of pod reconsiler


To use this run following commands:

```shell
make run
```

```shell
kubectl run --image=nginx my-nginx
```

```shell
kubectl annotate pod my-nginx cloudpirates.io/add-pod-name-label=true
```

