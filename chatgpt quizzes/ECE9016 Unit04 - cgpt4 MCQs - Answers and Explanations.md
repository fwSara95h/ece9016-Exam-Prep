1. What defines Container Orchestration in cloud computing?
   - **Answer: B) Automated deployment, scaling, and networking of containers**
   - **Explanation:** Container orchestration automates the deployment, scaling, and management of containerized applications, ensuring they run efficiently and reliably.

---

2. Which platform is not associated with container orchestration?
   - **Answer: D) Microsoft Excel**
   - **Explanation:** Microsoft Excel is a spreadsheet application and does not relate to container orchestration, unlike Docker Swarm, Kubernetes, and Apache Mesos, which are all designed for managing containers.

---

3. What is the smallest deployable unit in Kubernetes?
   - **Answer: C) Pod**
   - **Explanation:** In Kubernetes, a Pod is the smallest and simplest unit that you can create or deploy. It represents a single instance of a running process in your cluster.

---

4. Kubernetes Services are not used for:
   - **Answer: C) Automated scaling**
   - **Explanation:** While Kubernetes services provide load balancing and internal communication, automated scaling of services is managed by other Kubernetes components like the Horizontal Pod Autoscaler.

---

5. What does a Kubernetes Node not do?
   - **Answer: B) Scale automatically**
   - **Explanation:** Kubernetes nodes themselves do not scale automatically; this functionality is managed by the cluster control plane and often through integrations with cloud provider services.

---

6. What is not a feature of Kubernetes?
   - **Answer: B) Intrinsic data encryption**
   - **Explanation:** While Kubernetes offers many features, intrinsic data encryption at rest within the cluster is typically handled by external tools or cloud providers, not Kubernetes itself.

---

7. The primary role of etcd in Kubernetes is:
   - **Answer: B) Data storage for cluster state**
   - **Explanation:** etcd is a key-value store used to maintain the state of a Kubernetes cluster, ensuring that the cluster configuration is kept consistent across all nodes.

---

8. Kubernetes' scheduling of pods is based on:
   - **Answer: C) Resource requirements**
   - **Explanation:** Kubernetes schedules pods based on resource requirements and other constraints to ensure efficient and effective use of infrastructure.

---

9. In Kubernetes, a Service does not:
   - **Answer: C) Automatically update application versions**
   - **Explanation:** Kubernetes services handle traffic routing and load balancing, but they do not manage application version updates, which are handled by other components like Deployments.

---

10. Labels in Kubernetes are used for all except:
    - **Answer: B) Assisting with storage provisioning**
    - **Explanation:** Labels in Kubernetes are key-value pairs attached to objects and are used mainly for organizing and selecting subsets of objects, not for assisting directly with storage provisioning.

---

11. Kubernetes Pods share:
    - **Answer: D) Network namespaces**
    - **Explanation:** All containers within a pod share the same network namespace, meaning they share an IP address and port space.

---

12. The default service type in Kubernetes is:
    - **Answer: C) ClusterIP**
    - **Explanation:** The default service type in Kubernetes is ClusterIP, which exposes the service on an internal IP in the cluster, making it reachable only from within the cluster.

---

13. Kubernetes Services provide all except:
    - **Answer: A) Persistent storage**
    - **Explanation:** Kubernetes services provide features like service discovery, load balancing, and a consistent endpoint for pod access but do not provide persistent storage.

---

14. What does not describe a Kubernetes ClusterIP service?
    - **Answer: A) Exposes the service externally**
    - **Explanation:** ClusterIP services are designed for internal access within the cluster, not for external exposure.

---

15. Kubernetes NodePort service is not characterized by:
    - **Answer: C) Only operating within the cluster**
    - **Explanation:** NodePort services expose services externally by opening a specific port on each node, which is accessible from outside the Kubernetes cluster.

---

16. A Kubernetes LoadBalancer service does not:
    - **Answer: C) Restrict access to within the cluster**
    - **Explanation:** A LoadBalancer service creates an external load balancer to route external traffic to Kubernetes services, not just within the cluster.

---

17. Kubernetes DNS-based service discovery does not:
    - **Answer: B) Change DNS names frequently**
    - **Explanation:** DNS-based service discovery in Kubernetes provides stable DNS names for services, which do not change frequently unless explicitly reconfigured.

---

18. Kubernetes namespaces are not used for:
    - **Answer: A) Increasing computing power**
    - **Explanation:** Namespaces in Kubernetes are used for separating resources among different teams or projects, not for increasing computing power.

---

19. In Kubernetes, a ReplicaSet does not:
    - **Answer: B) Load balance between pods**
    - **Explanation:** A ReplicaSet ensures a specified number of pod replicas are running at any time and replaces failed pods, but it does not perform load balancing, which is handled by Services.

---

20. A Deployment in Kubernetes does not:
    - **Answer: A) Directly handle low-level networking**
    - **Explanation:** Deployments manage pods and replicas but do not directly handle networking, which is managed by Services and other networking resources.

---

21. Kubernetes' Horizontal Pod Autoscaler does not:
    - **Answer: B) Automatically update images**
    - **Explanation:** The Horizontal Pod Autoscaler adjusts the number of pod replicas based on CPU usage or other metrics but does not handle image updates, which are part of deployment strategies.

---

22. Kubernetes persistent volumes do not:
    - **Answer: D) Automatically create data backups**
    - **Explanation:** Persistent volumes provide storage that persists beyond the lifecycle of individual pods but do not automatically handle data backups, which require additional configuration or services.

---

23. In Kubernetes, Service Discovery is primarily facilitated by:
    - **Answer: C) DNS-based service discovery**
    - **Explanation:** Kubernetes uses DNS-based service discovery to allow services and pods to locate each other through DNS names, simplifying communication within the cluster.

---

24. Kubernetes' main approach to deployment strategy does not include:
    - **Answer: B) Blue-green deployment by default**
    - **Explanation:** While Kubernetes supports rolling updates and canary deployments, blue-green deployments are not provided out of the box and typically require additional configuration or tools.

---

25. The primary use of Kubernetes Ingress is not:
    - **Answer: A) Load balancing internal traffic**
    - **Explanation:** Kubernetes Ingress is primarily used for managing external access to services in a cluster, routing HTTP traffic, and providing network security enhancements like SSL/TLS termination, but it does not specifically target internal traffic load balancing.

---

26. Kubernetes ConfigMaps are typically not used for:
    - **Answer: A) Storing database credentials**
    - **Explanation:** ConfigMaps are designed for storing non-confidential data, such as configuration files and environment variables. Sensitive data like database credentials should be stored in Secrets, not ConfigMaps.

---

27. Kubernetes' automatic bin packing feature does not:
    - **Answer: C) Allocate resources arbitrarily**
    - **Explanation:** Kubernetes' scheduler optimizes resource usage by placing pods based on their resource requirements and other scheduling criteria, not arbitrarily.

---

28. A Kubernetes Secret is not intended for:
    - **Answer: C) Exposing confidential data to unauthorized users**
    - **Explanation:** Kubernetes Secrets are used specifically to store and handle sensitive information like passwords and tokens securely, ensuring such data is not exposed to unauthorized users.

---

29. What is not a standard practice for Kubernetes label usage?
    - **Answer: C) Utilizing labels for storage allocation**
    - **Explanation:** While labels are versatile for organizing and selecting Kubernetes resources, they are not used for storage allocation decisions directly.

---

30. Kubernetes' self-healing mechanism does not include:
    - **Answer: D) Ignoring pod failures**
    - **Explanation:** Kubernetes actively monitors pod status and takes action to replace or restart failed pods, rather than ignoring their failures.

---

31. The Kubernetes Scheduler does not:
    - **Answer: A) Allocate pods to nodes with insufficient resources**
    - **Explanation:** The scheduler ensures pods are placed on nodes that have sufficient resources to meet the pods' requirements, not the other way around.

---

32. Kubernetes Volumes do not:
    - **Answer: D) Enhance the network bandwidth of pods**
    - **Explanation:** Kubernetes volumes are used for data storage and persistence but do not affect network bandwidth.

---

33. Horizontal Pod Autoscaling in Kubernetes does not respond to:
    - **Answer: C) Decrease in network traffic**
    - **Explanation:** Horizontal Pod Autoscaler adjusts the number of pod replicas based on metrics like CPU or custom metrics usage, not network traffic conditions.

---

34. Kubernetes Labels are not:
    - **Answer: A) Immutable once set on an object**
    - **Explanation:** Labels can be modified after they are set on Kubernetes objects. They are not immutable and can be changed or updated as needed.

---

35. A Kubernetes Deployment does not:
    - **Answer: D) Directly manage hardware level settings**
    - **Explanation:** Kubernetes Deployments focus on managing applications at the container level, not directly interfacing with or managing hardware settings.

---

36. What component in Kubernetes acts as the front-end for the control plane?
   - **Answer: C) API Server**
   - **Explanation:** The API Server acts as the front-end interface to the Kubernetes control plane, handling and processing all REST requests and updating objects in etcd.

---

37. What is the primary role of etcd in a Kubernetes cluster?
   - **Answer: B) Data storage for cluster state**
   - **Explanation:** etcd is a consistent and highly-available key value store used as Kubernetes' backing store for all cluster data and state.

---

38. Which Kubernetes component is responsible for scheduling pods?
   - **Answer: B) Scheduler**
   - **Explanation:** The Scheduler is responsible for allocating pods to nodes in a cluster based on resource availability and other constraints.

---

39. What describes the Controller Manager's function in Kubernetes?
   - **Answer: B) Handles routine tasks within the cluster**
   - **Explanation:** The Controller Manager oversees a number of smaller controllers that regulate different aspects of cluster behavior, such as ensuring the correct number of pods are running.

---

40. In Kubernetes, what does Kubelet do?
   - **Answer: B) Manages a node's containers**
   - **Explanation:** The Kubelet is an agent running on each node, ensuring that containers are running in a Pod.

---

41. What is the primary function of kube-proxy in a Kubernetes environment?
   - **Answer: C) Network proxy on each node**
   - **Explanation:** kube-proxy maintains network rules on nodes, allowing network communication to your Pods from network sessions inside or outside of your cluster.

---

42. Which type of Kubernetes object is used for deploying stateful applications?
   - **Answer: C) StatefulSet**
   - **Explanation:** StatefulSets are the Kubernetes objects used for managing stateful applications because they provide unique, persistent identifiers and stable storage.

---

43. How are Kubernetes pods typically defined and deployed?
   - **Answer: C) Via YAML or JSON manifest files**
   - **Explanation:** Pods and other Kubernetes resources are typically defined and deployed using YAML or JSON configuration files, which specify their desired state.

---

44. What Kubernetes concept allows you to update applications without downtime?
   - **Answer: B) Rolling updates**
   - **Explanation:** Rolling updates allow Kubernetes deployments to update applications incrementally, with zero downtime, by gradually replacing instances of the old version of an application with the new version.

---

45. How do Kubernetes services enable communication between different pods?
   - **Answer: B) Through label selectors**
   - **Explanation:** Kubernetes services use label selectors to identify the pods that form part of the service, enabling communication between different pods.

---

46. What is not a type of service in Kubernetes?
   - **Answer: B) NodeBalancer**
   - **Explanation:** Kubernetes supports ClusterIP, NodePort, LoadBalancer, and ExternalName services. NodeBalancer is not a recognized type of service in Kubernetes.

---

47. What feature of Kubernetes allows automatic scaling of pods based on CPU usage?
   - **Answer: C) Horizontal Pod Autoscaler**
   - **Explanation:** The Horizontal Pod Autoscaler automatically scales the number of pods in a replication controller, deployment, replica set, or stateful set based on observed CPU utilization.

---

48. In Kubernetes, what is a ClusterIP?
   - **Answer: B) A service that exposes a pod to the cluster internally**
   - **Explanation:** A ClusterIP is an internal-only IP address that is used by services to enable internal process communications within a Kubernetes cluster.

---

49. What is the function of a Kubernetes NodePort service?
   - **Answer: A) Assigns a specific port on each node to access a service**
   - **Explanation:** A NodePort service in Kubernetes makes a service accessible on a specific port of each node in the cluster, thereby enabling external access to the service.

---

50. Which Kubernetes component is used for automated rollouts and rollbacks of applications?
   - **Answer: A) Deployment**
   - **Explanation:** Deployments in Kubernetes manage the rollout and rollback of applications, ensuring updates and version changes are handled smoothly.

---

51. What Kubernetes resource is used to manage external access to the services within a cluster?
   - **Answer: A) Ingress**
   - **Explanation:** Ingress is used to manage access to services from outside the Kubernetes cluster, routing traffic and handling external access.

---

52. How is data persisted across pod restarts in Kubernetes?
   - **Answer: B) Using persistent volumes**
   - **Explanation:** Persistent volumes in Kubernetes are used to persist data across pod restarts, ensuring data survives beyond the life of individual pods.

---

53. Which command is used to fetch the list of nodes in a Kubernetes cluster?
   - **Answer: C) kubectl get nodes**
   - **Explanation:** The command `kubectl get nodes` is used to list all nodes within a Kubernetes cluster, showing their status and roles.

---

54. What is not a recommended best practice for Kubernetes labels?
   - **Answer: B) Over-labeling resources for detailed tracking**
   - **Explanation:** Over-labeling can create unnecessary complexity and management overhead, making it difficult to maintain and understand resource relationships and roles.

---

55. In Kubernetes, what is the default machine type for a cluster created in Autopilot mode?
   - **Answer: C) e2-medium**
   - **Explanation:** The default machine type for Kubernetes clusters in GKE Autopilot mode is typically an e2-medium, balancing cost and performance efficiently.

---

56. What command sets the default compute region in GKE?
   - **Answer: C) gcloud config set compute/region**
   - **Explanation:** The command `gcloud config set compute/region` is used to set the default compute region for Google Kubernetes Engine and other GCP services.

---

57. What is the purpose of deploying a multi-container Pod in Kubernetes?
   - **Answer: C) To support co-located, co-managed helper containers**
   - **Explanation:** Multi-container pods are used when containers need to share resources tightly and communicate directly, such as helper containers that support a primary application.

---

58. How is a new Kubernetes cluster created in GKE using the command line?
   - **Answer: B) gcloud container clusters create**
   - **Explanation:** The command `gcloud container clusters create` is used to create a new cluster in Google Kubernetes Engine via the command line.

---

59. What is NOT a function of a Kubernetes Deployment?
   - **Answer: B) Automatic bin packing**
   - **Explanation:** While Deployments manage pods and their scaling, automatic bin packing, which involves efficiently distributing workloads across available compute resources, is handled by the Kubernetes scheduler, not Deployments.

---

60. What type of Kubernetes service allows external traffic to reach your cluster?
   - **Answer: D) LoadBalancer**
   - **Explanation:** A LoadBalancer service in Kubernetes provides an external IP that acts as a load balancer for incoming internet traffic to the services in the cluster.

---

61. How do Kubernetes labels assist in the management of resources?
   - **Answer: B) By categorizing resources for easier querying and management**
   - **Explanation:** Labels are key-value pairs that are used to organize and select groups of objects within Kubernetes, facilitating easier management and operation of clusters.

---

62. In Kubernetes, what does the 'RollingUpdate' strategy imply?
   - **Answer: B) Sequential update of pods without downtime**
   - **Explanation:** A RollingUpdate strategy in Kubernetes allows Deployments to update one pod at a time, seamlessly without taking down the entire service, thus avoiding downtime.

---

63. What is the purpose of a Kubernetes Secret?
   - **Answer: B) Storing sensitive information like passwords**
   - **Explanation:** Kubernetes Secrets are used to hold sensitive information such as passwords, tokens, or keys, helping to protect such data from unauthorized access.

---

64. What defines a 'Readiness Probe' in Kubernetes?
   - **Answer: A) Checks if a container is ready to handle requests**
   - **Explanation:** A Readiness Probe in Kubernetes is used to determine if a container is ready to start accepting traffic, helping to manage the traffic flow to pods efficiently.

---

65. What is not recommended when creating Kubernetes labels?
   - **Answer: B) Applying too many labels to a single resource**
   - **Explanation:** Using too many labels can complicate resource management and queries, making it difficult to maintain clarity and purpose of resource categorization.

---

66. How can you manually scale a deployment in Kubernetes?
   - **Answer: B) Modifying the deployment's replica count**
   - **Explanation:** Scaling a deployment in Kubernetes can be done by adjusting the number of replicas specified in the Deployment, which controls how many copies of a pod should run.

---

67. What is not a standard field in a Kubernetes YAML file for a Pod?
   - **Answer: C) replicas**
   - **Explanation:** The 'replicas' field is not used in a Pod specification as it is a single deployment unit; it is used in higher-level controllers like Deployments or ReplicaSets.

---

68. Which component is not part of a Kubernetes Node?
   - **Answer: C) Scheduler**
   - **Explanation:** The Scheduler is a part of the Kubernetes control plane that assigns pods to nodes, not a component that runs on each node.

---

69. What is the primary use of NodePort in Kubernetes?
   - **Answer: B) Assigning a specific port on each node to access a service**
   - **Explanation:** NodePort exposes a service on a static port on the node's IP address, allowing external traffic to access a service inside the cluster.

---

70. In Kubernetes, what is the role of the 'Controller Manager'?
   - **Answer: D) Running controller processes to regulate the state of the cluster**
   - **Explanation:** The Controller Manager runs various controllers that handle routine tasks necessary to ensure the desired state of the cluster as specified in Kubernetes objects.
