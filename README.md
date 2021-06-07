# k8s-manifests

## Manifests

- [calico.yaml](./calico.yaml) - Described and placed at [official on-premises documentation](https://docs.projectcalico.org/getting-started/kubernetes/self-managed-onprem/onpremises).
  - `kubectl apply -f https://raw.githubusercontent.com/luma-dev/k8s-manifests/main/calico.yaml`
- [calico-kubeadm-dualstack.yaml](./calico-kubeadm-dualstack.yaml) - Patched [calico.yaml](./calico.yaml) based on [official dualstack documentation](https://docs.projectcalico.org/networking/ipv6#enable-dual-stack)
  - `kubectl apply -f https://raw.githubusercontent.com/luma-dev/k8s-manifests/main/calico-kubeadm-dualstack.yaml`
