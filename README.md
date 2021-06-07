# k8s-manifests

## Manifests

- [calico.yaml](./calico.yaml) - Described and placed at [official on-premises documentation](https://docs.projectcalico.org/getting-started/kubernetes/self-managed-onprem/onpremises).
  - `kubectl apply -f https://raw.githubusercontent.com/luma-dev/k8s-manifests/main/calico.yaml`
- [calico-kubeadm-dualstack.yaml](./calico-kubeadm-dualstack.yaml) - Patched [calico.yaml](./calico.yaml) based on [official dualstack documentation](https://docs.projectcalico.org/networking/ipv6#enable-dual-stack) and [VA Linux's article about k8s ipv6](https://valinux.hatenablog.com/entry/20200722).
- [calico-kubeadm-dualstack-vultr-private.yaml](./calico-kubeadm-dualstack-vultr-private.yaml) - Patched [calico-kubeadm-dualstack.yaml](./calico-kubeadm-dualstack.yaml) based on [VA Linux's article about k8s ipv6](https://valinux.hatenablog.com/entry/20200722) customized for Vultr Ubuntu20.04 instances with private networking.
  - `kubectl apply -f https://raw.githubusercontent.com/luma-dev/k8s-manifests/main/calico-kubeadm-dualstack-vultr-private.yaml`
