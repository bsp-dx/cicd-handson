### AWS EKS 인증 정보 받기
```bash
aws eks update-kubeconfig --name (EKS 클러스터명) --alias (KubeConfig 에 저장될 이름)
```

### Istio Gateway Resource 조회 (Toolchain Namespace)
```bash
kubectl get gw -n toolchain --context (KubeConfig 에 저장된 이름)
```

### 각종 리소스 조회 (Default Namespace)
```bash
# Gateway, Virtual Service, Service, ReplicaSet, Pod
kubectl get gw,vs,svc,rs,pod -n default --context (KubeConfig 에 저장된 이름)
```
