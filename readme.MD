# Selectors

Tain the node
```
kubectl taint nodes ip-192-168-20-88.ec2.internal hardware=gpu:NoSchedule
```

untaint the node
```
kubectl taint nodes ip-192-168-20-88.ec2.internal hardware=gpu:NoSchedule-
```

Labeling the node
```

kubectl label nodes ip-192-168-37-109.ec2.internal hardware=gpu
```

Ref: https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes/ 