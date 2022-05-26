[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# CAPI LB Helm Charts



### Prerequisites
  - Kubernetes 1.9.2+
  - Helm v3.3.1

### Test with default localhost self signed certificates
```sh
helm install capi ./capi-charts
```

### Check if CAPI is running
```sh
kubectl get svc
```
