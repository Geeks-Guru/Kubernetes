## Les secrets sur Kubernetes

```
apiVersion: v1
kind: Secret
metadata:
  name: secret-sa-sample
  annotations:
    kubernetes.io/service-account.name: "sa-name"
type: kubernetes.io/service-account-token
data:
  # You can include additional key value pairs as you do with Opaque Secrets
  extra: YmFyCg==
```
## Authors

- [@Ulrich NOUMSI](https://www.linkedin.com/in/ulrich-steve-noumsi/)

