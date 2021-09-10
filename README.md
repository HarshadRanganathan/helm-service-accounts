# helm-service-accounts

Helm chart for creating service accounts in the cluster.

## Install/Upgrade Chart

Run below command to create service accounts:

```bash
helm upgrade -i service-accounts service-accounts --values=stages/prod/prod-values.yaml
```
