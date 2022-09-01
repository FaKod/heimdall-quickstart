# Heimdall K8s Demo

```bash
kind create cluster # wait until started
kubectl -k . # wait until deployed
kubectl port-forward svc/proxy 4455 # does not return
curl -v localhost:4455/foobar # other console
```