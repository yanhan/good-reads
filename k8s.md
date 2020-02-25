# About

Kubernetes

## Lists

- https://kubedex.com/


## Practical Walkthroughs

- https://eksworkshop.com/


## Quick guides (theory)

- https://medium.com/tech-tajawal/understand-kubernetes-main-concepts-in-2-minutes-68270fa3ceb6
- https://medium.com/yld-engineering-blog/kubernetes-core-concepts-324ea7028c29
- https://tutorialedge.net/blog/my-notes-for-certified-kubernetes/


## Container Runtime Interface (CRI)

- https://kubernetes.io/blog/2016/12/container-runtime-interface-cri-in-kubernetes/
- https://www.ianlewis.org/en/container-runtimes-part-1-introduction-container-r


## Kubernetes

- https://twitter.com/b0rk/status/943580770186260480 (Julia Evans: post about how her team at Stripe learnt to operate Kubernetes)
- https://www.youtube.com/watch?v=HlAXp0-M6SY (Kubernetes for Sysadmins - Kelsey Hightower at PuppetConf 2016)
- https://www.youtube.com/watch?v=YkOY7DgXKyw (Building a Bank with Kubernetes by Oliver Beattie, Monzo)
- http://blog.kubernetes.io/2015/06/the-distributed-system-toolkit-patterns.html


## Basic

- https://kubernetes.io/docs/tutorials/stateless-application/hello-minikube/
- https://www.youtube.com/watch?v=4ht22ReBjno (The Illustrated Children's Guide to Kubernetes)


## How to install

- https://blog.alexellis.io/kubernetes-in-10-minutes/
- https://kubernetes.io/docs/setup/independent/install-kubeadm/
- https://blog.jorgecastro.org/2017/07/21/tldring-your-way-to-a-kubernetes-bare-metal-cluster/


## How k8s can break

- https://twitter.com/b0rk/status/1108154770211119104?s=03 (how kubernetes can break)


## kustomize

- https://github.com/kubernetes-sigs/kustomize/blob/master/docs/fields.md


## Helm

- https://docs.bitnami.com/kubernetes/how-to/create-your-first-helm-chart/
- https://helm.sh/docs/chart_template_guide/


## CNI (Container Network Interface)

- https://rancher.com/blog/2019/2019-03-21-comparing-kubernetes-cni-providers-flannel-calico-canal-and-weave/


## Minikube

- https://askubuntu.com/a/768310 (sign kernel modules when minikube complains)


## Load Balancing

- https://medium.com/pablo-perez/k8s-externaltrafficpolicy-local-or-cluster-40b259a19404


## RBAC

- https://stackoverflow.com/questions/51612976/how-to-view-members-of-subject-with-group-kind/51636136#51636136


## PSP (PodSecurityPolicy)

- https://github.com/kubernetes/kubernetes/issues/71787#issuecomment-444894042 (how psps are chosen)
- https://banzaicloud.com/blog/pod-security-policy/


## EKS

- https://twitter.com/mhausenblas/status/1169292857108324353?s=19 (IAM roles for k8s service accounts)
- https://docs.aws.amazon.com/eks/latest/userguide/add-user-role.html (adding IAM users and IAM roles as k8s cluster user)
- https://docs.aws.amazon.com/eks/latest/userguide/launch-workers.html (launch nodes in EKS)
- https://docs.aws.amazon.com/eks/latest/userguide/network_reqs.html
- https://github.com/pulumi/pulumi-eks/issues/18 (Worker node cloud-init failure because they are launched into public subnets. Solution is to restrict them to private subnets only)
- https://github.com/terraform-aws-modules/terraform-aws-eks/issues/183#issuecomment-435877738 (Permissions required by EKS service role to create ELB)
- https://github.com/terraform-providers/terraform-provider-aws/issues/10104#issuecomment-565547413 (EKS OIDC provider CA cert thumbprint)
- https://github.com/vmware-tanzu/velero-plugin-for-aws/issues/17 (IAM role for service account: use `fsGroup` to get permissions to read token)

### Essential addons

- https://aws.amazon.com/premiumsupport/knowledge-center/eks-cluster-autoscaler-setup/
- https://github.com/kubernetes-incubator/external-dns/blob/master/docs/tutorials/aws.md
- https://github.com/kubernetes-incubator/metrics-server
- https://kubernetes.io/docs/tasks/administer-cluster/dns-horizontal-autoscaling/ (coredns cluster proportional autoscaler)
- https://github.com/kubernetes-incubator/cluster-proportional-autoscaler

### Optional addons

- https://docs.aws.amazon.com/eks/latest/userguide/alb-ingress.html
- https://github.com/kubernetes/ingress-nginx/blob/master/docs/deploy/index.md
- https://docs.cert-manager.io/en/latest/tutorials/acme/quick-start/index.html


## Exposing service via domain name

- https://github.com/kubernetes-incubator/external-dns


## Autoscaling

- https://github.com/kubernetes/autoscaler/blob/master/cluster-autoscaler/FAQ.md


## Graceful Pod Termination

- https://blog.gruntwork.io/zero-downtime-server-updates-for-your-kubernetes-cluster-902009df5b33
- https://blog.gruntwork.io/gracefully-shutting-down-pods-in-a-kubernetes-cluster-328aecec90d
- https://blog.gruntwork.io/delaying-shutdown-to-wait-for-pod-deletion-propagation-445f779a8304
- https://blog.gruntwork.io/avoiding-outages-in-your-kubernetes-cluster-using-poddisruptionbudgets-ef6a4baa5085


## Deploying code

- https://sanderknape.com/2019/02/automated-deployments-kubernetes-gitlab/


## Monitoring

- https://sysdig.com/blog/kubernetes-monitoring-prometheus-operator-part3/
- https://blog.colinbreck.com/kubernetes-liveness-and-readiness-probes-revisited-how-to-avoid-shooting-yourself-in-the-other-foot/


## Backup

- https://github.com/vmware-tanzu/velero


## Operators

- https://blog.openshift.com/kubernetes-operators-best-practices/
- https://medium.com/@cloudark/kubernetes-operator-faq-e018132c6ea2 (k8s Operator FAQ)


## Prometheus Operator

- https://blog.pilosus.org/posts/2019/06/01/prometheus-operator-no-active-targets/ (ServiceMonitor cannot find active targets)
- https://stackoverflow.com/a/56406404 (ServiceMonitor cannot find active targets)


## Debugging

- https://github.com/kubernetes-incubator/metrics-server/issues/130#issuecomment-508667085 (metrics-server unable to fetch metrics from kubelet solution: `--kubelet-preferred-address-types=InternalIP`)
- https://stackoverflow.com/questions/44736101/kubectl-get-hpa-targetsunknow/44736377#44736377 (HPA targets `<unknown>/20%`; need to specify `resources` in container spec)
- https://github.com/kubernetes/kops/issues/1796#issuecomment-329938319 (cluster-autoscaler needs `dnsPolicy: Default` if running on nodes without core-dns)
- https://news.ycombinator.com/item?id=21711748 (A visual guide on troubleshooting Kubernetes deployments)


## Linux capabilities

- https://danwalsh.livejournal.com/69478.html (`DAC_OVERRIDE`)


## Datadog

- https://github.com/DataDog/datadog-agent/issues/2816#issuecomment-513975368 (custom metrics and HPA, use `sum`)
