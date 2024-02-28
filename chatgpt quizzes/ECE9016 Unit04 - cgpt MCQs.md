1. What defines Container Orchestration in cloud computing?
   - A) Manual container management
   - B) Automated deployment, scaling, and networking of containers
   - C) Solely load balancing
   - D) Only for local systems

---
2. Which platform is not associated with container orchestration?
   - A) Docker Swarm
   - B) Kubernetes
   - C) Apache Mesos
   - D) Microsoft Excel

---
3. What is the smallest deployable unit in Kubernetes?
   - A) Node
   - B) Cluster
   - C) Pod
   - D) Service

---
4. Kubernetes Services are not used for:
   - A) Exposing applications
   - B) Load balancing
   - C) Automated scaling
   - D) Internal communication

---
5. What does a Kubernetes Node not do?
   - A) Host applications
   - B) Scale automatically
   - C) Run Pods
   - D) Manage networking

---
6. What is not a feature of Kubernetes?
   - A) Automated rollouts
   - B) Intrinsic data encryption
   - C) Self-healing
   - D) Service discovery

---
7. The primary role of etcd in Kubernetes is:
   - A) Load balancing
   - B) Data storage for cluster state
   - C) Managing network policies
   - D) Directing traffic to pods

---
8. Kubernetes' scheduling of pods is based on:
   - A) Random allocation
   - B) Fixed assignments
   - C) Resource requirements
   - D) Alphabetical ordering

---
9. In Kubernetes, a Service does not:
   - A) Assign DNS names to pods
   - B) Balance load across pods
   - C) Automatically update application versions
   - D) Enable communication between pods

---
10. Labels in Kubernetes are used for all except:
    - A) Organizing resources
    - B) Assisting with storage provisioning
    - C) Selecting subsets of objects
    - D) Managing resource allocation

---
11. Kubernetes Pods share:
    - A) Different IP addresses
    - B) The same lifecycle
    - C) Independent storage volumes
    - D) Network namespaces

---
12. The default service type in Kubernetes is:
    - A) NodePort
    - B) LoadBalancer
    - C) ClusterIP
    - D) ExternalName

---
13. Kubernetes Services provide all except:
    - A) Persistent storage
    - B) A consistent endpoint for pod access
    - C) Load balancing
    - D) Service discovery

---
14. What does not describe a Kubernetes ClusterIP service?
    - A) Exposes the service externally
    - B) Accessible within the cluster
    - C) Assigns a unique internal IP address
    - D) Used for internal communication

---
15. Kubernetes NodePort service is not characterized by:
    - A) Exposing a service externally
    - B) Assigning a unique port across all nodes
    - C) Only operating within the cluster
    - D) Allowing external traffic access

---
16. A Kubernetes LoadBalancer service does not:
    - A) Create an external load balancer
    - B) Assign a fixed external IP
    - C) Restrict access to within the cluster
    - D) Distribute external traffic efficiently

---
17. Kubernetes DNS-based service discovery does not:
    - A) Assign unique DNS names to services
    - B) Change DNS names frequently
    - C) Allow internal communication via consistent names
    - D) Simplify service interconnectivity

---
18. Kubernetes namespaces are not used for:
    - A) Increasing computing power
    - B) Separating cluster resources between teams
    - C) Organizing objects
    - D) Enabling multiple environments

---
19. In Kubernetes, a ReplicaSet does not:
    - A) Ensure a certain number of pods run
    - B) Load balance between pods
    - C) Replace failed pods
    - D) Manage pod replicas

---
20. A Deployment in Kubernetes does not:
    - A) Directly handle low-level networking
    - B) Manage pod versions and replicas
    - C) Provide declarative updates
    - D) Enable rollbacks

---
21. Kubernetes' Horizontal Pod Autoscaler does not:
    - A) Scale pods based on CPU usage
    - B) Automatically update images
    - C) Adjust the number of pod replicas
    - D) Respond to resource demand

---
22. Kubernetes persistent volumes do not:
    - A) Provide temporary storage
    - B) Persist data beyond pod lifecycle
    - C) Support multiple storage backends
    - D) Integrate with externalstorage configurations
    - D) Automatically create data backups

---
23. In Kubernetes, Service Discovery is primarily facilitated by:
    - A) Manual IP address management
    - B) Hard-coding Pod IP addresses
    - C) DNS-based service discovery
    - D) Using environment variables for service endpoints

---
24. Kubernetes' main approach to deployment strategy does not include:
    - A) Rolling updates
    - B) Blue-green deployment by default
    - C) Canary deployments
    - D) Immediate replacement

---
25. The primary use of Kubernetes Ingress is not:
    - A) Load balancing internal traffic
    - B) Managing external access to services
    - C) Routing HTTP traffic
    - D) Providing network security

---
26. Kubernetes ConfigMaps are typically not used for:
    - A) Storing database credentials
    - B) Running stateful applications
    - C) Configuring application settings
    - D) Supplying environment variables

---
27. Kubernetes' automatic bin packing feature does not:
    - A) Optimize resource usage based on requirements
    - B) Prioritize pods based on resource needs
    - C) Allocate resources arbitrarily
    - D) Ensure efficient use of node resources

---
28. A Kubernetes Secret is not intended for:
    - A) Encrypting data at rest
    - B) Storing sensitive information, such as passwords
    - C) Exposing confidential data to unauthorized users
    - D) Integrating with containerized applications

---
29. What is not a standard practice for Kubernetes label usage?
    - A) Using labels to indicate deployment environments
    - B) Labeling resources for organizational purposes
    - C) Utilizing labels for storage allocation
    - D) Applying labels to filter resources during selection

---
30. Kubernetes' self-healing mechanism does not include:
    - A) Automatically replacing failed nodes
    - B) Restarting containers that fail health checks
    - C) Moving workloads to healthy nodes
    - D) Ignoring pod failures

---
31. The Kubernetes Scheduler does not:
    - A) Allocate pods to nodes with insufficient resources
    - B) Schedule pods based on resource availability
    - C) Ensure that pods are placed on appropriate nodes
    - D) Balance pod distribution across the cluster

---
32. Kubernetes Volumes do not:
    - A) Persist data after pod deletion
    - B) Share data between multiple containers in a pod
    - C) Store configuration files and secrets
    - D) Enhance the network bandwidth of pods

---
33. Horizontal Pod Autoscaling in Kubernetes does not respond to:
    - A) Changes in memory usage
    - B) CPU load increases
    - C) Decrease in network traffic
    - D) Specific custom metrics thresholds

---
34. Kubernetes Labels are not:
    - A) Immutable once set on an object
    - B) Key-value pairs used for organization
    - C) Utilized for selecting subsets of objects
    - D) Mandatory for all Kubernetes objects

---
35. A Kubernetes Deployment does not:
    - A) Guarantee stateful application consistency
    - B) Enable declarative updates for pods and replicasets
    - C) Support automated rollbacks
    - D) Directly manage hardware level settings

---
36. What component in Kubernetes acts as the front-end for the control plane?
   - A) Kubelet
   - B) etcd
   - C) API Server
   - D) Controller Manager

---
37. What is the primary role of etcd in a Kubernetes cluster?
   - A) Service discovery
   - B) Data storage for cluster state
   - C) Load balancing
   - D) Managing container runtime

---
38. Which Kubernetes component is responsible for scheduling pods?
   - A) API Server
   - B) Scheduler
   - C) Kubelet
   - D) etcd

---
39. What describes the Controller Manager's function in Kubernetes?
   - A) Manages network traffic
   - B) Handles routine tasks within the cluster
   - C) Stores sensitive information
   - D) Schedules pods on nodes

---
40. In Kubernetes, what does Kubelet do?
   - A) Provides cluster-wide DNS
   - B) Manages a node's containers
   - C) Balances network traffic
   - D) Stores cluster configuration

---
41. What is the primary function of kube-proxy in a Kubernetes environment?
   - A) Data encryption
   - B) Managing deployments
   - C) Network proxy on each node
   - D) Monitoring container health

---
42. Which type of Kubernetes object is used for deploying stateful applications?
   - A) Deployment
   - B) Service
   - C) StatefulSet
   - D) ConfigMap

---
43. How are Kubernetes pods typically defined and deployed?
   - A) Through Docker Compose files
   - B) Using imperative commands only
   - C) Via YAML or JSON manifest files
   - D) Directly through the Docker CLI

---
44. What Kubernetes concept allows you to update applications without downtime?
   - A) Persistent volumes
   - B) Rolling updates
   - C) Pod affinity
   - D) Node selectors

---
45. How do Kubernetes services enable communication between different pods?
   - A) By defining storage requirements
   - B) Through label selectors
   - C) By assigning each pod a public IP address
   - D) Using API versioning

---
46. What is not a type of service in Kubernetes?
   - A) ClusterIP
   - B) NodeBalancer
   - C) LoadBalancer
   - D) NodePort

---
47. What feature of Kubernetes allows automatic scaling of pods based on CPU usage?
   - A) Kube-scheduler
   - B) AutoScaler
   - C) Horizontal Pod Autoscaler
   - D) Vertical Pod Autoscaler

---
48. In Kubernetes, what is a ClusterIP?
   - A) An external IP address for accessing the cluster
   - B) A service that exposes a pod to the cluster internally
   - C) A specific type of pod deployment
   - D) The IP address of the master node

---
49. What is the function of a Kubernetes NodePort service?
   - A) Assigns a specific port on each node to access a service
   - B) Automatically configures a cloud load balancer
   - C) Creates a private, internal-only IP address
   - D) Schedules pods across different nodes

---
50. Which Kubernetes component is used for automated rollouts and rollbacks of applications?
   - A) Deployment
   - B) Service
   - C) Volume
   - D) Ingress

---
51. What Kubernetes resource is used to manage external access to the services within a cluster?
   - A) Ingress
   - B) Endpoint
   - C) ClusterIP
   - D) Egress

---
52. How is data persisted across pod restarts in Kubernetes?
   - A) Through stateful sets
   - B) Using persistent volumes
   - C) By saving data in container layer
   - D) Through Kubernetes secrets

---
53. Which command is used to fetch the list of nodes in a Kubernetes cluster?
   - A) kubectl get pods
   - B) kubectl list nodes
   - C) kubectl get nodes
   - D) kubectl nodes show

---
54. What is not a recommended best practice for Kubernetes labels?
   - A) Using a clear and consistent labeling scheme
   - B) Over-labeling resources for detailed tracking
   - C) Utilizing labels for affinity and anti-affinity
   - D) Applying labels for efficient resource allocation

---
55. In Kubernetes, what is the default machine type for a cluster created in Autopilot mode?
   - A) e2-highcpu
   - B) e2-standard
   - C) e2-medium
   - D) n1-standard

---
56. What command sets the default compute region in GKE?
   - A) gcloud config set compute/zone
   - B) kubectl set region
   - C) gcloud config set compute/region
   - D) kube-region set compute

---
57. What is the purpose of deploying a multi-container Pod in Kubernetes?
   - A) To increase the cluster size
   - B) For running unrelated applications together
   - C) To support co-located, co-managed helper containers
   - D) To reduce the number of services

---
58. How is a new Kubernetes cluster created in GKE using the command line?
   - A) kubectl create cluster
   - B) gcloud container clusters create
   - C) gcloud services enable Kubernetes
   - D) kube-init start cluster

---
59. What is NOT a function of a Kubernetes Deployment?
   - A) Rolling back to an earlier version
   - B) Automatic bin packing
   - C) Managing a set of pods
   - D) Updating pods with a new image

---
60. What type of Kubernetes service allows external traffic to reach your cluster?
   - A) ClusterIP
   - B) NodePort
   - C) InternalName
   - D) LoadBalancer

---
61. How do Kubernetes labels assist in the management of resources?
   - A) By encrypting data stored within resources
   - B) By categorizing resources for easier querying and management
   - C) By increasing the computational power of resources
   - D) By automatically scaling resources up and down

---
62. In Kubernetes, what does the 'RollingUpdate' strategy imply?
   - A) Immediate replacement of all pods
   - B) Sequential update of pods without downtime
   - C) Update all pods simultaneously causing downtime
   - D) Scaling down all pods before updating

---
63. What is the purpose of a Kubernetes Secret?
   - A) Scheduling pods on nodes
   - B) Storing sensitive information like passwords
   - C) Exposing a service to the internet
   - D) Managing storage for pods

---
64. What defines a 'Readiness Probe' in Kubernetes?
   - A) Checks if a container is ready to handle requests
   - B) Verifies the container's deployment status
   - C) Confirms the node's health and availability
   - D) Ensures data encryption within pods

---
65. What is not recommended when creating Kubernetes labels?
   - A) Using concise and descriptive labels
   - B) Applying too many labels to a single resource
   - C) Labeling resources based on their environment
   - D) Using labels to denote log levels

---
66. How can you manually scale a deployment in Kubernetes?
   - A) Adjusting the CPU limits
   - B) Modifying the deployment's replica count
   - C) Changing the image version
   - D) Editing the service type

---
67. What is not a standard field in a Kubernetes YAML file for a Pod?
   - A) apiVersion
   - B) kind
   - C) replicas
   - D) metadata

---
68. Which component is not part of a Kubernetes Node?
   - A) Kubelet
   - B) Docker
   - C) Scheduler
   - D) Kube-proxy

---
69. What is the primary use of NodePort in Kubernetes?
   - A) Allocating storage to nodes
   - B) Assigning a specific port on each node to access a service
   - C) Distributing nodes across different zones
   - D) Encrypting data transmitted between nodes

---
70. In Kubernetes, what is the role of the 'Controller Manager'?
   - A) Assigning IP addresses to services
   - B) Managing the lifecycle of pods
   - C) Orchestrating container storage
   - D) Running controller processes to regulate the state of the cluster

---
---

**Answer Key:**
1. B
2. D
3. C
4. C
5. B
6. B
7. B
8. C
9. C
10. B
11. D
12. C
13. A
14. A
15. C
16. C
17. A
18. B
19. B
20. B
21. B
22. C
23. C
24. B
25. A
26. B
27. C
28. C
29. C
30. A
31. A
32. D
33. C
34. A
35. A
36. C
37. B
38. B
39. B
40. B
41. C
42. C
43. C
44. B
45. B
46. B
47. C
48. B
49. A
50. A
51. A
52. B
53. C
54. B
55. D
56. C
57. C
58. B
59. B
60. D
61. B
62. B
63. B
64. A
65. B
66. B
67. C
68. C
69. B
70. D
