1. What automates the deployment, management, scaling, and networking of containers?
   - Container Orchestration.
---
2. What is Kubernetes' role in cloud computing?
   - Managing life cycles of containers, especially in large dynamic environments.
---
3. What are Kubernetes' key goals in container orchestration?
   - Efficient Resource Utilization, High Availability, Scalability, Load Balancing.
---
4. What are the benefits of Container Orchestration?
   - Simplified Management, Automated Deployment and Management, Enhanced Security.
---
5. What are some examples of Container Orchestration tools?
   - Docker Swarm, Apache Mesos.
---
6. What defines Kubernetes (K8s)?
   - An open-source platform for automating deployment, scaling, and operations of application containers across clusters.
---
7. What are Kubernetes Main Features?
   - Container Management, Service Discovery and Load Balancing, Storage Orchestration, Automated Rollouts and Rollbacks, Self-Healing, Secret and Configuration Management.
---
8. What are common use cases of Kubernetes?
   - Microservices Architecture, Cloud-native Applications, CI/CD Pipelines.
---
9. What constitutes a Kubernetes Cluster?
   - A set of Nodes that run containerized applications.
---
10. What are the roles of Master and Worker Nodes in Kubernetes?
   - Master Node makes global decisions, Worker Nodes execute the work.
---
11. What are the characteristics of Kubernetes Pods?
   - Smallest deployable units, hosts one or more containers, shares network storage.
---
12. What are Kubernetes Services?
   - Abstractions defining logical sets of Pods and consistent methods to access them.
---
13. What are Kubernetes Labels and Selectors?
   - Key-value pairs attached to objects for identification, organization, and selection based on criteria.
---
14. What is the kubectl tool used for?
   - Communicating with the cluster.
---
15. What does a Kubernetes Volume provide?
   - A way to store data accessible by containers in a Pod.
---
16. What are Kubernetes Namespaces used for?
   - Allowing multiple teams or projects to use the same cluster without conflict.
---
17. Describe the types of Services in Kubernetes.
   - ClusterIP, NodePort, LoadBalancer.
---
18. What is ClusterIP service type used for in Kubernetes?
   - Internal communication within the cluster.
---
19. How does NodePort service type work in Kubernetes?
   - Exposes the service on each Node’s IP at a static port, allowing external traffic.
---
20. What is the purpose of the LoadBalancer service in Kubernetes?
   - Creates an external load balancer and assigns a fixed external IP to the service.
---
21. How is service discovery achieved in Kubernetes?
   - DNS-based service discovery, assigning DNS names to services.
---
22. What is the purpose of Kubernetes' rolling updates?
   - To update applications with zero downtime.
---
23. How can you scale a deployment in Kubernetes?
   - Update the replicas field in YAML file or use the kubectl scale command.
---
24. What command removes a deployment and its associated resources in Kubernetes?
   - kubectl delete deployment <deployment-name>.
---
25. Describe Kubernetes' approach to managing application configurations.
   - Using ConfigMaps and Secrets for managing and integrating sensitive information with containerized applications.
---
26. How are containers scheduled onto nodes in Kubernetes?
   - Using the Kubernetes scheduler based on resource requirements and other constraints.

27. What is the role of 'etcd' in a Kubernetes cluster?
   - It stores all cluster data, acting as the cluster's "source of truth."

28. Describe the purpose of a Kubernetes 'Deployment'.
   - To manage the deployment and scaling of a set of pods and to provide declarative updates to applications.

29. What does a Kubernetes 'Service' define?
   - An abstraction that defines a logical set of pods and a policy by which to access them.

30. How can you roll back a deployment in Kubernetes?
   - By using the 'kubectl rollout undo' command.

31. What is a 'NodePort' service in Kubernetes?
   - A service that makes a pod accessible from outside the Kubernetes cluster using a port allocated on each node.

32. Explain 'LoadBalancer' service in Kubernetes context.
   - It provisions an external load balancer for a service, making it accessible from the internet.

33. What is 'Horizontal Pod Autoscaler' in Kubernetes?
   - A feature that automatically scales the number of pods in a replication controller, deployment, or replica set based on observed CPU utilization.

34. How does Kubernetes handle persistent storage?
   - Through PersistentVolumes that are mounted into pods.

35. What is the significance of 'namespaces' in Kubernetes?
   - They allow multiple teams to use the same cluster with isolated resources.

36. What is the primary function of 'Kube-proxy' in Kubernetes?
   - To maintain network rules on nodes, allowing network communication to pods from network sessions inside or outside the cluster.

37. Describe the process of updating a Kubernetes application without downtime.
   - By using rolling updates in deployments, which ensure no downtime by incrementally updating pods instances with new ones.

38. What are 'labels' and 'selectors' in Kubernetes?
   - Key-value pairs attached to objects for organizing and selecting subsets of objects.

39. How does 'Kubelet' work within a Kubernetes node?
   - It ensures that containers are running in a pod.

40. What is the main advantage of Kubernetes auto-scaling feature?
   - It automatically adjusts the number of running instances based on the actual load.

41. How do you expose a Kubernetes pod to the external network?
   - By creating a service of type LoadBalancer or NodePort.

42. What is the purpose of the 'kubectl expose' command?
   - To expose a resource like a pod, deployment, or service as a new Kubernetes service.

43. How can you monitor the health of Kubernetes services?
   - By using liveness and readiness probes.

44. What does a 'StatefulSet' in Kubernetes ensure?
   - It manages the deployment and scaling of a set of pods, and provides guarantees about the ordering and uniqueness of these pods.

45. What is the role of 'Ingress' in Kubernetes?
   - To manage external access to the services in a cluster, typically HTTP.

46. How do you create a new Kubernetes cluster using kubectl?
   - kubectl does not directly create a cluster; this is done using cloud provider tools or kubeadm.

47. How can you view all resources in a specific namespace in Kubernetes?
   - By using 'kubectl get all --namespace=<namespace>'.

48. What is the purpose of resource quotas in Kubernetes namespaces?
   - To limit the aggregate resource consumption in a namespace.

49. How do you list all pods running in the Kubernetes cluster?
   - By using 'kubectl get pods'.

50. What are 'DaemonSets' in Kubernetes?
   - They ensure that a copy of a pod runs on all (or some) nodes in the cluster.
---
51. What is the role of 'etcd' in Kubernetes?
   - Acts as the central store for all Kubernetes cluster data.
---
52. How can you expose a pod to the external internet in Kubernetes?
   - By creating a Service of type LoadBalancer.
---
53. What command is used to get the version of the Kubernetes cluster?
   - `kubectl version`
---
54. How does Kubernetes ensure that applications remain available during an update?
   - Through rolling updates.
---
55. What Kubernetes resource is used to automatically scale the number of pods?
   - Horizontal Pod Autoscaler.
---
56. What is the significance of the 'replicas' field in a Kubernetes Deployment?
   - It specifies the desired number of pod instances.
---
57. What is a Kubernetes Ingress used for?
   - Managing external access to the services in a cluster.
---
58. How do you roll back a deployment to a previous state in Kubernetes?
   - Using the `kubectl rollout undo` command.
---
59. What is the default scheduling strategy of Kubernetes?
   - Distribute workloads across all available nodes to ensure efficient resource use.
---
60. How do labels and selectors work together in Kubernetes?
   - Labels assign properties to objects, selectors filter objects based on these labels.
---
61. What is the purpose of Kubernetes Namespaces?
   - To divide cluster resources between multiple users.
---
62. How can you list all the services in a Kubernetes cluster?
   - `kubectl get services`
---
63. What is the function of a Kubernetes ConfigMap?
   - To store non-confidential data in key-value pairs.
---
64. How is persistent storage implemented in Kubernetes?
   - Through PersistentVolumes and PersistentVolumeClaims.
---
65. What command is used to apply a configuration to a resource in Kubernetes?
   - `kubectl apply -f <filename>`
---
66. How do you delete all resources under a specific namespace in Kubernetes?
   - `kubectl delete all --all -n <namespace>`
---
67. What ensures high availability of pods in Kubernetes?
   - ReplicaSets and Replication Controllers.
---
68. How can you update the image of a container in a running pod in Kubernetes?
   - By updating the Deployment that manages the pod.
---
69. What is the Kubernetes command to view detailed information about a specific pod?
   - `kubectl describe pod <pod-name>`
---
70. How do you create a new namespace in Kubernetes?
   - `kubectl create namespace <namespace-name>`
---
71. What is the role of the Kube-proxy in Kubernetes?
   - To handle networking and communication within the cluster.
---
72. What is a DaemonSet in Kubernetes?
   - A way to ensure that some or all nodes run a copy of a pod.
---
73. How do you view the logs of a container in a pod in Kubernetes?
   - `kubectl logs <pod-name> -c <container-name>`
---
74. What is the command to list all nodes in a Kubernetes cluster?
   - `kubectl get nodes`
---
75. How do you scale a deployment in Kubernetes without using the YAML file?
   - `kubectl scale deployment <deployment-name> --replicas=<num>`
---
76. What Kubernetes resource limits the number of pods that can run on each node?
   - Node resource limits.
---
77. How can you specify which nodes a pod should be scheduled on in Kubernetes?
   - Using node selector labels.
---
78. What feature allows Kubernetes pods to share the same lifecycle, storage, and network?
   - Pod affinity.
---
79. How does Kubernetes handle secret management?
   - Through Kubernetes Secrets.
---
80. What is the purpose of Kubernetes persistent volumes?
   - To provide a persistent storage mechanism for data.
---
81. How can you view detailed information about a specific Kubernetes service?
   - Using `kubectl describe service <service-name>`.
---
82. What command updates a Kubernetes deployment with a new image?
   - `kubectl set image deployment/<deployment-name> <container-name>=<new-image>`.
---
83. How does Kubernetes provide DNS for services?
   - Through CoreDNS or Kube-DNS.
---
84. What Kubernetes object is responsible for keeping a set number of pods running?
   - ReplicaSet.
---
85. How can you access the Kubernetes dashboard?
   - By deploying the Kubernetes Dashboard and accessing it through a proxy.
---
86. What is the default protocol for services when no protocol is specified in Kubernetes?
   - TCP.
---
87. How does Kubernetes handle pod scaling?
   - Through Horizontal Pod Autoscaler or manual scaling.
---
88. How are Kubernetes services accessed from outside the cluster without using an external IP?
   - Through Ingress or NodePort services.
---
89. What is the command to list all pods in a specific Kubernetes namespace?
   - `kubectl get pods --namespace=<namespace>`.
---
90. How can you ensure a pod’s storage persists beyond its lifecycle?
   - By using PersistentVolumes and PersistentVolumeClaims.
---
91. What is the purpose of Kubernetes network policies?
   - To control the traffic flow between pods/containers.
---
92. How can you delete all resources in a Kubernetes namespace?
   - `kubectl delete all --all --namespace=<namespace>`.
---
93. What is a StatefulSet in Kubernetes?
   - Used for managing stateful applications.
---
94. How do you expose a Kubernetes pod as a service?
   - By creating a Service resource pointing to the pod.
---
95. What type of Kubernetes service should be used to expose a service to the internet?
   - LoadBalancer.
---
96. How can you retrieve the logs of a specific container in a Kubernetes pod?
   - `kubectl logs <pod-name> -c <container-name>`.
---
97. What is required to enable a Kubernetes service to be discovered by DNS?
   - The service must have a valid name and selector.
---
98. What command gives you the status of a Kubernetes roll-out?
   - `kubectl rollout status deployment/<deployment-name>`.
---
99. How can you rollback a Kubernetes deployment to a previous revision?
   - `kubectl rollout undo deployment/<deployment-name>`.
---
100. What is the primary function of the Kube-scheduler?
   - To schedule pods on nodes based on resource availability and constraints.
