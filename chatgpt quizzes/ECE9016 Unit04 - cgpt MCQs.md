1. What is the main goal of container orchestration?
   - A) Minimizing cloud storage costs
   - B) Automating container deployment and management
   - C) Reducing the number of containers in use
   - D) Increasing manual intervention in container management
---
2. Which platform is primarily associated with container orchestration?
   - A) Docker Swarm
   - B) Kubernetes
   - C) Apache Mesos
   - D) Microsoft Azure
---
3. What defines a Kubernetes Pod?
   - A) A group of related Docker containers
   - B) A single instance of a Kubernetes service
   - C) The smallest deployable unit in Kubernetes
   - D) A type of Kubernetes storage volume
---
4. What is the purpose of a Kubernetes Service?
   - A) To automate image building and versioning
   - B) To provide a persistent storage solution
   - C) To enable communication between different pods
   - D) To manage the Kubernetes API versions
---
5. What is the role of a Node in a Kubernetes cluster?
   - A) To store container images
   - B) To manage networking between containers
   - C) To host the running containers
   - D) To monitor container performance
---
6. Which Kubernetes object is used to manage a set of replicas of a pod?
   - A) Deployment
   - B) Volume
   - C) Service
   - D) ConfigMap
---
7. What is the function of the Kubernetes Scheduler?
   - A) To distribute network traffic across containers
   - B) To assign pods to nodes
   - C) To encrypt sensitive data within pods
   - D) To replicate containers across multiple nodes
---
8. What is a typical use case for Kubernetes?
   - A) Data encryption
   - B) Load balancing
   - C) Microservice architecture
   - D) Single-sign-on authentication
---
9. How does Kubernetes achieve high availability?
   - A) By restricting pod communication
   - B) By automatically replacing failed pods
   - C) By using a single master node
   - D) By deploying all pods on a single node
---
10. What does the 'kubectl' command-line tool do?
    - A) Manages Docker images
    - B) Provides a user interface for Kubernetes
    - C) Interacts with the Kubernetes cluster
    - D) Monitors container performance in real-time
---
11. What is the purpose of Kubernetes labels?
    - A) To schedule backups
    - B) To organize objects like pods and services
    - C) To define network policies
    - D) To create new container images
---
12. What type of Kubernetes object is a 'Service'?
    - A) A storage unit
    - B) A networking rule
    - C) An access control policy
    - D) An abstraction to access pods
---
13. How does Kubernetes handle service discovery?
    - A) Through manual configuration
    - B) Using a centralized service directory
    - C) With DNS-based discovery
    - D) By assigning public IP addresses to each service
---
14. What is a Kubernetes ClusterIP service?
    - A) An external load balancer
    - B) An internal endpoint for cluster communication
    - C) A public-facing service endpoint
    - D) A private Docker registry
---
15. What enables communication between Kubernetes clusters?
    - A) ClusterIP services
    - B) External databases
    - C) NodePort services
    - D) Ingress controllers
---
16. What is a characteristic of a Kubernetes NodePort service?
    - A) Exposes a service to internal traffic only
    - B) Automatically scales the service based on traffic
    - C) Exposes the service on a static port on each node
    - D) Provides encrypted connections to the service
---
17. What is the primary use of a Kubernetes Deployment?
    - A) Managing stateful applications
    - B) Providing persistent storage
    - C) Automating the deployment and scaling of pods
    - D) Balancing network traffic
---
18. What is the Kubernetes Control Plane responsible for?
    - A) Running application containers
    - B) Directly handling external traffic
    - C) Managing cluster state and configuration
    - D) Storing container images
---
19. In Kubernetes, what is a pod's lifecycle managed by?
    - A) A Deployment or ReplicaSet
    - B) A StatefulSet
    - C) A DaemonSet
    - D) A Service
---
20. What does the Kubernetes command 'kubectl scale' do?
    - A) Changes the number of cluster nodes
    - B- Increases the number of pod replicas
    - C) Adjusts the number of active pods for a deployment
    - D) Updates the Kubernetes API version
---
21. How are Kubernetes Services different from Kubernetes Deployments?
    - A) Services provide a persistent storage interface
    - B) Services abstract pod access by a consistent name and port
    - C) Deployments automate image builds
    - D) Deployments offer external network access
---
22. What does 'kubectl delete' command achieve?
    - A) Updates a pod's configuration
    - B) Removes specified resources from the cluster
    - C) Restarts a stopped pod
    - D) Scales down a deployment
---
23. How does Kubernetes' self-healing mechanism work?
    - A) By manually restarting failed containers
    - B) By automatically replacing failed pods
    - C) Through user intervention
    - D) Using external monitoring tools
---
24. What role does the etcd component play in Kubernetes?
    - A) Load balancing
    - B) Data encryption
    - C) Stores cluster state and configuration
    - D) Manages network policies
---
25. How does Kubernetes' automatic bin packing feature function?
    - A) Prioritizes bin storage
    - B) Allocates resources based on container needs
    - C) Packs containers into the smallest possible space
    - D) Automatically deletes unused bins
---
26. What distinguishes Kubernetes node types?
    - A) Their physical location
    - B) Their roles within the cluster (Master vs. Worker)
    - C) The type of pods they can host
    - D) The operating system they run
---
27. What is a Kubernetes ReplicaSet primarily used for?
    - A) Managing network traffic
    - B) Ensuring a specified number of pod replicas are running
    - C) Replicating databases
    - D) Copying files between pods
---
28. What is Kubernetes Volume used for?
    - A) Storing sensitive data
    - B) Providing a temporary storage area for pods
    - C) Providing persistent storage for pods
    - D) Increasing the memory available to pods
---
29. How does a Kubernetes LoadBalancer Service operate?
    - A) By redirecting traffic to avoid overload
    - B) By distributing incoming network traffic across multiple pods
    - C) By balancing computational load across nodes
    - D) By limiting the rate of network requests
---
30. What is the primary purpose of Kubernetes Namespaces?
    - A) To provide additional security
    - B) To manage different environments within the same cluster
    - C) To increase the number of available pods
    - D) To offer load balancing services
---
31. What feature does Kubernetes offer for update rollbacks?
    - A) Manual pod replacement
    - B) Automated rollouts and rollbacks
    - C) Instantaneous update application
    - D) Update pause and resume
---
32. What does a Kubernetes Service 'ClusterIP' provide?
    - A) A permanent IP address for each node
    - B) A static IP address for external access
    - C) An internal IP address accessible within the cluster
    - D) A dynamic IP address assigned to each service
---
33. What is the main purpose of the Kubernetes Kube-proxy component?
    - A) To proxy the Kubernetes API server
    - B) To manage container runtime environments
    - C) To forward requests to the appropriate container
    - D) To encrypt container data
---
34. How do Labels and Selectors improve Kubernetes resource management?
    - A) By facilitating manual resource allocation
    - B) By enabling efficient and precise resource grouping
    - C) By limiting the number of resources used
    - D) By automatically generating resource labels
---
35. What is the typical content of a Kubernetes YAML file for deployment?
    - A) Cluster configuration settings
    - B) Image registry credentials
    - C) Specifications for creating pods and services
    - D) Network policy definitions

---
36. What command in Kubernetes is used to set the default compute region and zone for GKE?
   - A) gcloud config set compute/region
   - B) kubectl set region
   - C) gcloud set compute/zone
   - D) kubectl config set region
---
37. Which Kubernetes object is necessary for deploying a scalable and maintainable application?
   - A) Pod
   - B) ReplicaSet
   - C) Deployment
   - D) Service
---
38. What does the Kubernetes Deployment manage?
   - A) Database transactions
   - B) The network traffic
   - C) Pod creation, deletion, and updates
   - D) Cloud storage solutions
---
39. In Kubernetes, what is a NodePort service primarily used for?
   - A) Internal cluster communication
   - B) Exposing a service to external traffic
   - C) Load balancing within the cluster
   - D) Connecting pods across clusters
---
40. What feature of Kubernetes allows for automatic scaling of pods based on resource usage?
   - A) Horizontal Pod Autoscaler
   - B) Vertical Pod Autoscaler
   - C) Pod Lifecycle Manager
   - D) Resource Limit Controller
---
41. How do you expose a Kubernetes application to the internet?
   - A) Using a NodePort service
   - B) By creating a Deployment
   - C) Through a ClusterIP service
   - D) By deploying a Pod directly
---
42. What is the role of etcd in a Kubernetes cluster?
   - A) Data encryption
   - B) Load balancing
   - C) Store cluster state and configuration
   - D) Network routing
---
43. What type of service in Kubernetes assigns a unique IP address to each pod?
   - A) ClusterIP
   - B) NodePort
   - C) LoadBalancer
   - D) ExternalName
---
44. What Kubernetes resource is used to manage the lifecycle of a set of pods?
   - A) Service
   - B) Deployment
   - C) Volume
   - D) Namespace
---
45. How is a new Kubernetes cluster created in GKE?
   - A) gcloud container clusters create
   - B) kubectl create cluster
   - C) gcloud create gke-cluster
   - D) kubectl gke deploy
---
46. Which file type is commonly used for Kubernetes object specifications?
   - A) JSON
   - B) XML
   - C) YAML
   - D) HTML
---
47. What command is used to obtain cluster credentials in GKE?
   - A) gcloud container clusters get-credentials
   - B) kubectl get-credentials
   - C) gcloud get gke-credentials
   - D) kubectl access gke
---
48. What is the main advantage of using Kubernetes Autopilot mode in GKE?
   - A) Manual node management
   - B) Automated cluster and resources management
   - C) Direct access to physical servers
   - D) Fixed pricing
---
49. How can you scale a deployment in Kubernetes?
   - A) kubectl scale
   - B) kubectl resize
   - C) kubectl deploy-scale
   - D) kubectl modify
---
50. What command is used to apply changes to a Kubernetes deployment?
   - A) kubectl apply
   - B) kubectl update
   - C) kubectl refresh
   - D) kubectl commit
---
51. What Kubernetes concept allows you to run multiple clusters within the same physical infrastructure?
   - A) Virtual Nodes
   - B) Namespaces
   - C) Multi-Clusters
   - D) Cluster Groups
---
52. In Kubernetes, how are updates to Pods typically managed?
   - A) By directly updating each Pod
   - B) Through ReplicaSets
   - C) Using Deployment updates
   - D) With direct Pod replacement
---
53. What Kubernetes command is used to list all services in the cluster?
   - A) kubectl get services
   - B) kubectl list all-services
   - C) kubectl display services
   - D) kubectl services all
---
54. What is the primary function of the Kube-proxy in a Kubernetes cluster?
   - A) Data encryption
   - B) Monitoring resource usage
   - C) Handling network traffic routing
   - D) Managing pod lifecycle
---
55. How does Kubernetes provide high availability for applications?
   - A) Through manual intervention
   - B) By using a single, highly available node
   - C) Automatically replicating pods across multiple nodes
   - D) Through dedicated hardware
---

56. Which component is responsible for container orchestration within Kubernetes?
   - A) Docker
   - B) Kubelet
   - C) Kube-scheduler
   - D) Kube-proxy
---
57. What is the purpose of the Kubernetes API server?
   - A) To store data
   - B) To schedule pods
   - C) To serve the Kubernetes API
   - D) To manage network traffic
---
58. Which type of Kubernetes object can be used to manage a set of identical pods?
   - A) Service
   - B) Deployment
   - C) Volume
   - D) Namespace
---
59. What is the primary function of the kubelet?
   - A) Providing a user interface
   - B) Managing the node's containers
   - C) Load balancing
   - D) Network routing
---
60. What does Kubernetes use to automatically place pods onto nodes?
   - A) Labels
   - B) Selectors
   - C) Scheduler
   - D) Replicas
---
61. Which Kubernetes object is used to expose a pod to the network?
   - A) ReplicaSet
   - B) Deployment
   - C) Service
   - D) Volume
---
62. What does the 'kubectl create' command do?
   - A) Removes resources
   - B) Lists resources
   - C) Creates resources
   - D) Updates resources
---
63. What feature does Kubernetes provide for managing application configurations?
   - A) Pods
   - B) Deployments
   - C) ConfigMaps
   - D) StatefulSets
---
64. How does Kubernetes achieve fault tolerance?
   - A) By using a single, highly-available master node
   - B) Through manual intervention
   - C) By replicating services across multiple nodes
   - D) By restricting access to the cluster
---
65. In Kubernetes, what is a namespace used for?
   - A) To combine services
   - B) To manage different environments within the same cluster
   - C) To increase pod capacity
   - D) To link different clusters
---
66. How does Kubernetes monitor the health of applications?
   - A) Through external tools only
   - B) By using the kubectl health command
   - C) With liveness and readiness probes
   - D) By manual checking
---
67. What is the primary purpose of a Kubernetes Ingress?
   - A) To encrypt data
   - B) To automate deployments
   - C) To manage external access to the services
   - D) To monitor container performance
---
68. What command is used to view the logs of a Kubernetes pod?
   - A) kubectl logs
   - B) kubectl view
   - C) kubectl inspect
   - D) kubectl check
---
69. How can Kubernetes applications be scaled?
   - A) By changing the pod specifications
   - B) Using the kubectl scale command
   - C) By manually increasing the number of nodes
   - D) Through direct pod replication
---
70. What strategy does Kubernetes use to update applications?
   - A) Manual replacement of pods
   - B) Direct pod editing
   - C) Rolling updates
   - D) Stopping and restarting all pods


**Answer Key:**
1. B
2. B
3. C
4. C
5. C
6. A
7. B
8. C
9. B
10. C
11. B
12. D
13. C
14. B
15. C
16. C
17. C
18. C
19. A
20. C
21. B
22. B
23. B
24. C
25. B
26. B
27. B
28. C
29. B
30. B
31. B
32. C
33. C
34. B
35. C
    (Sorry the rest got lost)
56. C
57. C
58. B
59. B
60. C
61. C
62. C
63. C
64. C
65. B
66. C
67. C
68. A
69. B
70. C