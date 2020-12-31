## Instalation of Istio and services

Get istioctl from istio site.

```sh
istioctl install -f istioConfig.yaml

kubectl -f naca-gateway.yaml naca-virtual-service.yaml -n naca
```