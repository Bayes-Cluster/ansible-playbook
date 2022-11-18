# Kubeadm with K8s

Build a Kubernetes Cluster using [Ansible-playbook](https://www.ansible.com/) and [kubeadm](https://github.com/kubernetes/kubeadm). 

## Goal 

The goal is easily set-up a Kubernetes cluster on bare metal and virtual machines with:

1. multiple distributions:
    1. Ubuntu (>= 18.04)
    2. Debian (>= 9)
    3. CentOS (>= 7)
    4. [OpenCloudOS](https://www.opencloudos.org/) - in the future 
2. Kubernetes versions: 
    1. [v1.23](https://kubernetes.io/blog/2021/12/07/kubernetes-1-23-release-announcement/)
    2. [v1.24](https://kubernetes.io/blog/2022/05/03/kubernetes-1-24-release-announcement/)
    3. [v1.25](https://kubernetes.io/blog/2022/08/23/kubernetes-v1-25-release/)
3. Container Runtimes:
    1. [containerd](https://containerd.io/)
    2. [cri-o](https://cri-o.io/)
4. Container Network Interface(CNI): 
    1. [flannl](https://github.com/flannel-io/flannel)
    2. [calico](https://www.tigera.io/project-calico/)
    3. [cilium](https://cilium.io/)
5. Load Balancer (LB):
    1. [MetalLB](https://metallb.universe.tf/)
    2. [OpenELB](https://openelb.io/)
    3. [PureLB](https://purelb.gitlab.io/docs/)
    4. [Kube-VIP](https://kube-vip.io/) - in the future
5. Ingress Controllers:
    1. Nginx-based: [ingress-nginx](https://github.com/kubenetes/ingress-nginx) & [kubenetes-ingress](https://github.com/nginxinc/kubernetes-ingress)
    2. HAProxy-based: [haproxy-ingress](https://github.com/jcmoraisjr/haproxy-ingress) [Voyager](https://github.com/appscode/voyager)
    3. [Kong Ingress](https://github.com/Kong/kubernetes-ingress-controller)
    4. [Traefik](https://github.com/containous/traefik)
    5. Envoy-based: [Contour](https://projectcontour.io/) & [Ambassador](https://www.getambassador.io/)
