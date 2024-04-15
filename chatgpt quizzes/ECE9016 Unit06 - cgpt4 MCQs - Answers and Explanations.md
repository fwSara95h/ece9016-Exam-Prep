## WithOUT Slide Content Available
<sub>The answers below were generated without slide content available</sub>

1. What is the minimum disk size per node specified for the cluster configuration in the GKE cluster creation?
   - **Answer: C) 20 GB**
   - **Explanation:** The minimum recommended disk size per node in a GKE cluster is typically around 20 GB to ensure sufficient space for node operations and container workloads.

---

2. Which of the following Kubernetes commands is used to push a Docker image to a repository?
   - **Answer: A) docker push**
   - **Explanation:** The `docker push` command is used to push a Docker image to a Docker registry or repository.

---

3. In the Kubernetes environment, what type of service is `nginx-service` classified as?
   - **Answer: C) LoadBalancer**
   - **Explanation:** Without specific details, any of the listed types could be possible, but a common use case for a service like `nginx-service`, especially if external access is needed, is a LoadBalancer.

---

4. When deploying a Docker image, what command is used to tag the Docker image before pushing it to the repository?
   - **Answer: A) docker tag**
   - **Explanation:** The `docker tag` command is used to create a tag TARGET_IMAGE that refers to SOURCE_IMAGE, useful for versioning before pushing to a repository.

---

5. In the context of Kubernetes, what does the term "Pod Affinity" refer to?
   - **Answer: B) A set of rules that attract pods towards certain pods**
   - **Explanation:** Pod Affinity in Kubernetes allows you to specify rules that attract pods to nodes where other pods are located, based on labels.

---

6. What is the label key used in the pod anti-affinity setup mentioned in the document?
   - **Answer: D) app**
   - **Explanation:** Commonly, labels used in Kubernetes for affinity/anti-affinity rules involve keys like `app`, where `app=nginx` could be a typical example.

---

7. What port does the service-a LoadBalancer expose externally?
   - **Answer: C) 80**
   - **Explanation:** The most common port exposed by a LoadBalancer service for web traffic, such as one managing `nginx`, is port 80.

---

8. Which type of node affinity prevents a pod from being scheduled on certain nodes?
   - **Answer: C) Node anti-affinity**
   - **Explanation:** Node anti-affinity is used to prevent a pod from being scheduled on certain nodes, typically based on labels that the nodes have.

---

9. What is the purpose of the `kubectl describe pod` command in the Kubernetes workflow?
   - **Answer: B) To show detailed information about a specific pod**
   - **Explanation:** The `kubectl describe pod` command is used to display detailed information about a specific pod, including its status, volumes, and conditions.

---

10. What command is used to deploy a service file in Kubernetes?
    - **Answer: B) kubectl apply -f**
    - **Explanation:** The `kubectl apply -f` command is used to apply or deploy a configuration file in Kubernetes, including service definitions.

---

11. What machine type is specified for the creation of the GKE cluster mentioned in the document?
   - **Answer: C) E2 Medium**
   - **Explanation:** E2 Medium is a commonly chosen machine type for GKE clusters due to its balance of compute, memory, and network resources.

---

12. What Kubernetes component is used to manage traffic within a cluster?
   - **Answer: B) Service**
   - **Explanation:** A Service in Kubernetes is used to manage internal traffic within a cluster by defining a policy to access pods.

---

13. Which command is used to create a new Docker artifact repository?
   - **Answer: A) gcloud artifacts repositories create**
   - **Explanation:** The `gcloud artifacts repositories create` command is used within the Google Cloud environment to create a new repository for Docker artifacts.

---

14. In a Kubernetes deployment file, what is used to ensure that a pod is deployed to a node with specific characteristics?
   - **Answer: A) NodeSelector**
   - **Explanation:** `NodeSelector` is a field in the pod specification that specifies a map of key-value pairs that must be present on the node for the pod to be scheduled there.

---

15. What purpose does the `EXPOSE` command serve in a Dockerfile?
   - **Answer: D) It documents which ports the container will listen on**
   - **Explanation:** The `EXPOSE` instruction in a Dockerfile is used to inform Docker that the container listens on specific network ports. It is a form of documentation and does not actually publish the port.

---

16. In the document's context, what is the primary role of `service-a` in the microservices architecture?
   - **Answer: D) Load balancing**
   - **Explanation:** Typically, in microservices architecture, a service named with a generic identifier like `service-a` could be involved in tasks like load balancing, particularly if it is configured as a LoadBalancer.

---

17. What is the significance of using `ClusterIP` as a service type in Kubernetes?
   - **Answer: A) Exposes the service on a cluster-internal IP**
   - **Explanation:** A ClusterIP service type exposes the service on an internal IP within the cluster, making it only reachable from within the cluster.

---

18. Which file format is used for the deployment configuration in Kubernetes?
   - **Answer: A) YAML**
   - **Explanation:** YAML is the primary file format used for writing Kubernetes deployment configurations due to its readability and ease of use.

---

19. What action does the `kubectl get pods -o wide` command perform?
   - **Answer: A) Lists all pods in wide format including additional details**
   - **Explanation:** The `-o wide` option with `kubectl get pods` provides additional details about each pod in the list, such as the node they are running on and their IP addresses.

---

20. What is the effect of pod anti-affinity in Kubernetes?
    - **Answer: B) Prevents pods from being co-located on the same node**
    - **Explanation:** Pod anti-affinity ensures that pods do not share nodes, useful in scenarios where pods from the same application should not be on the same physical or virtual host for fault tolerance.

---

21. What geographical zone is the GKE cluster 'ap-cluster' deployed to?
   - **Answer: C) Asia East**
   - **Explanation:** 'ap-cluster' likely refers to a cluster deployed in the Asia Pacific region, with 'Asia East' being a common designation for a zone in that region.

---

22. What Kubernetes command is used to deploy the Nginx application mentioned in the document?
   - **Answer: A) kubectl apply -f nginx-deployment.yaml**
   - **Explanation:** `kubectl apply -f` is used to apply a configuration file, and `nginx-deployment.yaml` would be the file containing the deployment configuration for an Nginx application.

---

23. In the context of Kubernetes, what is the function of the selector `app:nginx`?
   - **Answer: A) Identifies all pods running Nginx**
   - **Explanation:** The selector `app:nginx` is used to identify and manage pods that are part of an application or service labeled as `nginx`.

---

24. Which Docker command creates a Docker image using a Dockerfile?
   - **Answer: C) docker build**
   - **Explanation:** The `docker build` command is used to create a Docker image from a Dockerfile, specifying the context and potential tag for the image.

---

25. What is the purpose of setting an external IP for a Kubernetes service?
   - **Answer: C) To allow external access to a service**
   - **Explanation:** Setting an external IP for a Kubernetes service is typically done to allow traffic from outside the cluster to reach the service.

---

26. How does pod affinity influence pod scheduling in Kubernetes?
   - **Answer: C) By encouraging the placement of pods on nodes with certain labels**
   - **Explanation:** Pod affinity in Kubernetes influences scheduling by encouraging the placement of pods on nodes that have specific labels, often matching those of other pods they should be located near.

---

27. What type of drive might a node affinity rule prefer for a pod in Kubernetes?
   - **Answer: A) SSD**
   - **Explanation:** Node affinity rules can specify preferences for nodes with certain types of storage, such as SSDs, which are faster and more suitable for I/O-intensive applications.

---

28. In a microservices architecture, what is the primary communication method between 'service-a' and 'service-b' as described?
   - **Answer: B) RESTful API requests**
   - **Explanation:** In microservices architectures, services typically communicate through RESTful API requests, allowing for lightweight, stateless communication.

---

29. What does the `kubectl get svc` command display?
   - **Answer: B) A list of all active services**
   - **Explanation:** The `kubectl get svc` command is used to list all the active services in the current or specified namespace, showing their type, cluster IP, external IP, ports, and age.

---

30. What is the primary advantage of using a LoadBalancer service in Kubernetes?
    - **Answer: C) It distributes incoming network traffic across multiple pods.**
    - **Explanation:** A LoadBalancer service in Kubernetes is designed to distribute incoming network traffic across multiple pods to ensure smooth handling of load and improve service availability.

