# Helm chart for deploying Pretend you're Xyzzy to K8s

Bare bones helm chart for deploying [Pretend you're Xyzzy](https://github.com/ajanata/PretendYoureXyzzy) to k8s.

see [values.yaml](pretend-youre-xyzzy/values.yaml) for configurations.

Install using Helm v3:

```
helm repo add flipenergy https://flipenergy.github.io/k8s-homelab/
helm install my-release flipenergy/pretend-youre-xyzzy
```
