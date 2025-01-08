# Kubernetes cluster deployment


## Components version


Name                     | Version              |
-------------------------|----------------------|
Kubernetes               | 1.30.8<br>1.31.4      |
Containerd               | 1.7.24<br>2.0.1       |
RunC                     | 1.1.15<br>1.2.4       |
CNI                      | 1.5.1<br>1.6.2        |
Calico                   | 3.28.2<br>3.29.1      |
MetalLB                  | 0.14.9               |
Ingress NGINX Controller | 1.11.4<br>1.12.0      |
NFS CSI driver           | 4.9.0(Chart 4.9.0)   |
Cert-manager             | 1.16.2               |
Metrics-server           | 0.7.2(Chart 3.12.2)  |



## Requirements

#### Kubernetes host:
- Ubuntu Server 22.04.5 LTS (Jammy Jellyfish)
- Ubuntu Server 24.04.1 LTS (Noble Numbat)

#### Ansible host:
```console
python=3.10 
python3-pip
ansible=9.12.0
ansible-core=2.16.13
```

## Source:

#### Kubernetes:
- https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/install-kubeadm/
- https://kubernetes.io/docs/setup/production-environment/container-runtimes/#install-and-configure-prerequisites
- https://kubernetes.io/releases/

#### Containerd:
- https://github.com/containerd/containerd/blob/main/docs/getting-started.md
- https://github.com/containerd/containerd 
- https://kubernetes.io/docs/setup/production-environment/container-runtimes/#containerd
- https://containerd.io/downloads/

#### RunC:
- https://github.com/opencontainers/runc

#### CNI:
- https://www.cni.dev/
- https://github.com/containernetworking/plugins

#### Calico:
- https://docs.tigera.io/calico/latest/getting-started/kubernetes/quickstart#install-calico
- https://docs.tigera.io/archive
- https://github.com/projectcalico/calico

#### MetalLB:
- https://metallb.universe.tf/installation/
- https://metallb.universe.tf/configuration/
- https://metallb.universe.tf/release-notes/
- https://github.com/metallb/metallb

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