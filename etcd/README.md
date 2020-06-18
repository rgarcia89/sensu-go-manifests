# Deploy using the following command

```bash
# Switch to the etcd directory
helm repo add bitnami https://charts.bitnami.com/bitnami
helm repo update
helm upgrade --install -f values/dev.yaml etcd bitnami/etcd
```

Change `initialClusterState` in values file on line 167 from `new` to `existing` after initial deploy.