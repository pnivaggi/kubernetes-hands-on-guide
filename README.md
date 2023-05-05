# Kubernetes Hands On

The repository includes a Kubernetes introduction training with hands on. Lab is built using Kind Kubernetes deployer. It follows the Certified Kubernetes Application Developper (CKAD) breakdown:

- [00.kubernetes-architecture](00.kubernetes-architecture.md)
- [01.getting-started](01.getting-started.md)
- [02.cluster-networking](02.cluster-networking.md)
- [03-kubectl](03-kubectl.md)
- [04.understanding-pods](04.understanding-pods.md)
- [05.understanding-namespaces](05.understanding-namespaces.md)
- [06.configuration](06.configuration.md)
- [07.multi-container-pods](07.multi-container-pods.md)
- [08.pod-design](08.pod-design.md)
- [09.hpa](09.hpa.md)
- [10.networking](10.networking.md)
- [11.services](11.services.md)
- [12.istio](12.istio.md)

The notions covered are the following:

- kubernetes-architecture: node, worker, control plane, api, primitives
- getting-started: docker, kind and kubectl installation, cluster deployment, kubectl config
- cluster-networking: docker networking, veth pairs
- kubectl: imperative vs declarative, create/apply/list/delete/edit/replace/update commands, manifest files
- understanding-pods: local and Docker based micoservices, Pod encapsulation, get logs and execute commands on Pod, Pod command/args config
- understanding-namespaces: create/delete namespace, resource quota, default namespace
- configuration: Pod env variables, ConfigMaps, Docker user/capabilities, Security context, Service Account
- multi-container-pods: init containers, sidecar, adapter/ambassador
- pod-design: label, selector, annotation, deployment, jobs and cronjobs
- horizontal pod autoscaler: Metrics server, horizontal Pod autoscaler, multiple and custom metrics
- networking: pod ip address, node ip routes, network policies
- services: clusterIP, kubectl proxy, NodePort, LoadBalancer
- Istio service mesh: install istio, virtual services, destination rules, kiali
