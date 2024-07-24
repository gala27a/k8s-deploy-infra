# Kubernetes cluster deployment


## Components version


Name                     | Version    |
-------------------------|------------|
Kubernetes               | 1.30.1     |
Containerd               | 1.7.17     |
RunC                     | 1.1.12     |
CNI                      | 1.5.0      |
Calico                   | 3.28.0     |
MetalLB                  | 0.14.5     |
Ingress NGINX Controller | 1.10.1     |
NFS CSI driver           | 4.7.0(Chart 4.7.0)  |
Cert-manager             | 1.15.1     |
Metrics-server           | 0.7.1(Chart 3.12.1) |



## Requirements

#### Kubernetes host:
> Ubuntu 22.04.4 LTS (Jammy Jellyfish)

#### Ansible host:
```console
python=3.10 
python3-pip
ansible=9.8.0
ansible-core=2.16.9
```

## Source:

#### Kubernetes:
- https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/install-kubeadm/
- https://kubernetes.io/docs/setup/production-environment/container-runtimes/#install-and-configure-prerequisites

#### Containerd:
- https://github.com/containerd/containerd/blob/main/docs/getting-started.md 
- https://kubernetes.io/docs/setup/production-environment/container-runtimes/#containerd
- https://containerd.io/downloads/

#### RunC:
- https://github.com/opencontainers/runc

#### CNI:
- https://www.cni.dev/
- https://github.com/containernetworking/plugins

#### Calico:
- https://docs.tigera.io/calico/latest/getting-started/kubernetes/quickstart#install-calico

#### MetalLB:
- https://metallb.universe.tf/installation/
- https://metallb.universe.tf/configuration/

#### Ingress NGINX Controller:
- https://github.com/kubernetes/ingress-nginx
- https://kubernetes.github.io/ingress-nginx/deploy/#quick-start
- https://kubernetes.io/docs/concepts/services-networking/ingress-controllers/

#### NFS CSI driver:
- https://kubernetes-csi.github.io/docs/drivers.html
- https://github.com/kubernetes-csi/csi-driver-nfs
- https://github.com/kubernetes-csi/csi-driver-nfs/tree/master/charts

#### Cert-manager:
- https://cert-manager.io/docs/installation/kubectl/
- https://github.com/cert-manager/cert-manager

#### Metrics-server:
- https://kubernetes-sigs.github.io/metrics-server/
- https://github.com/kubernetes-sigs/metrics-server
- https://artifacthub.io/packages/helm/metrics-server/metrics-server


## Contact
- Linkedin: https://www.linkedin.com/in/dawid-gala-3a3b9b1a2/