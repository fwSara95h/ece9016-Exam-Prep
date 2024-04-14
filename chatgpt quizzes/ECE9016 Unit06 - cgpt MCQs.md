1. What is the minimum disk size per node specified for the cluster configuration in the GKE cluster creation?
   - A) 5 GB
   - B) 10 GB
   - C) 20 GB
   - D) 15 GB
---
2. Which of the following Kubernetes commands is used to push a Docker image to a repository?
   - A) docker push
   - B) kubectl push
   - C) gcloud docker -- push
   - D) push docker
---
3. In the Kubernetes environment, what type of service is `nginx-service` classified as?
   - A) NodePort
   - B) ClusterIP
   - C) LoadBalancer
   - D) ExternalName
---
4. When deploying a Docker image, what command is used to tag the Docker image before pushing it to the repository?
   - A) docker tag
   - B) kubectl tag
   - C) gcloud docker -- tag
   - D) tag image
---
5. In the context of Kubernetes, what does the term "Pod Affinity" refer to?
   - A) A set of rules that repel pods from certain nodes
   - B) A set of rules that attract pods towards certain pods
   - C) A directive to spread pods evenly across all nodes
   - D) A method for automatically managing pod storage
---
6. What is the label key used in the pod anti-affinity setup mentioned in the document?
   - A) key=app
   - B) value=app
   - C) app=nginx
   - D) app
---
7. What port does the service-a LoadBalancer expose externally?
   - A) 8080
   - B) 8081
   - C) 80
   - D) 443
---
8. Which type of node affinity prevents a pod from being scheduled on certain nodes?
   - A) Soft node affinity
   - B) Hard node affinity
   - C) Node anti-affinity
   - D) Pod affinity
---
9. What is the purpose of the `kubectl describe pod` command in the Kubernetes workflow?
   - A) To list all pods in the cluster
   - B) To show detailed information about a specific pod
   - C) To delete a specific pod
   - D) To create a new pod
---
10. What command is used to deploy a service file in Kubernetes?
    - A) kubectl deploy service
    - B) kubectl apply -f
    - C) docker service deploy
    - D) kubectl create service
---
11. What machine type is specified for the creation of the GKE cluster mentioned in the document?
   - A) E2 Large
   - B) E2 Micro
   - C) E2 Medium
   - D) N1 Standard
---
12. What Kubernetes component is used to manage traffic within a cluster?
   - A) Ingress Controller
   - B) Service
   - C) Deployment
   - D) ConfigMap
---
13. Which command is used to create a new Docker artifact repository?
   - A) gcloud artifacts repositories create
   - B) docker repository init
   - C) kubectl create repository
   - D) gcloud docker --init-repo
---
14. In a Kubernetes deployment file, what is used to ensure that a pod is deployed to a node with specific characteristics?
   - A) NodeSelector
   - B) MatchExpressions
   - C) NodeConstraints
   - D) SelectLabels
---
15. What purpose does the `EXPOSE` command serve in a Dockerfile?
   - A) It publishes a container's port to the host
   - B) It exposes environment variables to the container
   - C) It makes the container visible to external networks
   - D) It documents which ports the container will listen on
---
16. In the document's context, what is the primary role of `service-a` in the microservices architecture?
   - A) Backend processing
   - B) Frontend user interface
   - C) Database management
   - D) Load balancing
---
17. What is the significance of using `ClusterIP` as a service type in Kubernetes?
   - A) Exposes the service on a cluster-internal IP
   - B) Exposes the service externally
   - C) Balances load between multiple services
   - D) None of the above
---
18. Which file format is used for the deployment configuration in Kubernetes?
   - A) YAML
   - B) JSON
   - C) XML
   - D) TXT
---
19. What action does the `kubectl get pods -o wide` command perform?
   - A) Lists all pods in wide format including additional details
   - B) Widens the scope of the get command to include all namespaces
   - C) Modifies pod settings to increase resource allocation
   - D) Retrieves detailed health information about each pod
---
20. What is the effect of pod anti-affinity in Kubernetes?
    - A) Ensures pods are scheduled on nodes with similar pods
    - B) Prevents pods from being co-located on the same node
    - C) Automatically reschedules pods to different nodes periodically
    - D) None of the above
---
21. What geographical zone is the GKE cluster 'ap-cluster' deployed to?
   - A) North America West
   - B) Europe West
   - C) Asia East
   - D) North America Northeast
---
22. What Kubernetes command is used to deploy the Nginx application mentioned in the document?
   - A) kubectl apply -f nginx-deployment.yaml
   - B) kubectl deploy nginx
   - C) docker run nginx
   - D) gcloud app deploy nginx
---
23. In the context of Kubernetes, what is the function of the selector `app:nginx`?
   - A) Identifies all pods running Nginx
   - B) Configures Nginx settings within a pod
   - C) Automatically scales Nginx pods
   - D) Updates Nginx versions across deployments
---
24. Which Docker command creates a Docker image using a Dockerfile?
   - A) docker compile
   - B) docker compose up
   - C) docker build
   - D) docker make
---
25. What is the purpose of setting an external IP for a Kubernetes service?
   - A) To enable inter-cluster communication
   - B) To enable intra-cluster communication
   - C) To allow external access to a service
   - D) To assign a static IP within the cluster
---
26. How does pod affinity influence pod scheduling in Kubernetes?
   - A) By ensuring pods are spread as widely as possible
   - B) By preventing pods from being scheduled on certain nodes
   - C) By encouraging the placement of pods on nodes with certain labels
   - D) By assigning pods to the node with the least load
---
27. What type of drive might a node affinity rule prefer for a pod in Kubernetes?
   - A) SSD
   - B) HDD
   - C) USB
   - D) SCSI
---
28. In a microservices architecture, what is the primary communication method between 'service-a' and 'service-b' as described?
   - A) Direct database access
   - B) RESTful API requests
   - C) Shared memory access
   - D) Asynchronous messaging
---
29. What does the `kubectl get svc` command display?
   - A) The current state of all nodes
   - B) A list of all active services
   - C) Deployment history of the cluster
   - D) Detailed pod information
---
30. What is the primary advantage of using a LoadBalancer service in Kubernetes?
    - A) It encrypts data traffic within the cluster.
    - B) It allows for automatic scaling of pods.
    - C) It distributes incoming network traffic across multiple pods.
    - D) It provides storage resources to pods.

---

#### Answer Key
1. B) 10 GB
2. A) docker push
3. C) LoadBalancer
4. A) docker tag
5. B) A set of rules that attract pods towards certain pods
6. D) app
7. C) 80
8. C) Node anti-affinity
9. B) To show detailed information about a specific pod
10. B) kubectl apply -f
11. C) E2 Medium
12. B) Service
13. A) gcloud artifacts repositories create
14. A) NodeSelector
15. D) It documents which ports the container will listen on
16. B) Frontend user interface
17. A) Exposes the service on a cluster-internal IP
18. A) YAML
19. A) Lists all pods in wide format including additional details
20. B) Prevents pods from being co-located on the same node
21. D) North America Northeast
22. A) kubectl apply -f nginx-deployment.yaml
23. A) Identifies all pods running Nginx
24. C) docker build
25. C) To allow external access to a service
26. C) By encouraging the placement of pods on nodes with certain labels
27. A) SSD
28. B) RESTful API requests
29. B) A list of all active services
30. C) It distributes incoming network traffic across multiple pods

