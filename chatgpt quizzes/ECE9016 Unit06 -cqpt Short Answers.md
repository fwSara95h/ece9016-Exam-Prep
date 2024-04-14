1. What is the cluster name of the GKE cluster created in the document?
   - Answer: ap-cluster
---
2. How many nodes are specified for the GKE cluster setup in the document?
   - Answer: 2 nodes
---
3. What is the machine type specified for the nodes in the GKE cluster?
   - Answer: E2 Medium
---
4. Which city's zone is targeted for deploying the GKE cluster?
   - Answer: Toronto zone a
---
5. What is the primary function of a LoadBalancer in Kubernetes?
   - Answer: To distribute incoming network traffic across multiple pods.
---
6. What is the command to create a Docker artifact repository as per the document?
   - Answer: gcloud artifacts repositories create
---
7. What type of storage size is mentioned for the nodes in the document?
   - Answer: Disk size per node 10 GB
---
8. What is Node Affinity in Kubernetes?
   - Answer: Node Affinity allows you to constrain which nodes your pod can be scheduled on based on node labels.
---
9. What is Pod Anti-Affinity?
   - Answer: Pod Anti-Affinity prevents pods from being co-located on the same node, based on labels.
---
10. Which command is used to expose Nginx to the Internet in the document?
    - Answer: kubectl apply -f nginx-service.yaml
---
11. What is the IP address of the nginx-service mentioned in the document?
    - Answer: 127.30.40.212
---
12. Which service is described as having a selector `app:service-a`?
    - Answer: service-a-balancer
---
13. What is the port number that service-a-balancer exposes?
    - Answer: 80
---
14. Which Docker base image is used in the Dockerfile for service-a?
    - Answer: python:3.8-slim
---
15. What command is used to create a new GKE cluster called 'ms-cluster'?
    - Answer: gcloud container clusters create ms-cluster
---
16. How does Kubernetes' Pod Affinity affect pod scheduling?
    - Answer: It encourages the co-location of pods within the same or in specific nodes based on labels.
---
17. What port is exposed by the Dockerfile used for service-b?
    - Answer: 8081
---
18. What environment variable is defined in the Dockerfile for the microservices?
    - Answer: NAME World
---
19. Which type of Kubernetes service is used for internal communication between pods?
    - Answer: ClusterIP
---
20. What type of Kubernetes object is used to manage external access to the services?
    - Answer: LoadBalancer
---
21. What Kubernetes resource is used to deploy the nginx application mentioned in the document?
   - Answer: Deployment YAML File
---
22. What command updates the Kubernetes deployment with the specified deployment file?
   - Answer: kubectl apply -f nginx-deployment.yaml
---
23. Which node label might be targeted for Node Affinity to ensure a pod runs on a node with an SSD drive?
   - Answer: A node label indicating the presence of an SSD drive.
---
24. What specific anti-affinity rule is used to avoid placing a new instance of a database pod on a node that already hosts another instance of the same database pod?
   - Answer: Node Anti-Affinity
---
25. What function does the `kubectl describe pod` command perform in Kubernetes?
   - Answer: It provides detailed information about a specific pod.
---
26. In the document, what type of affinity prevents new pods from being scheduled on the same node as other specified pods?
   - Answer: Pod Anti-Affinity
---
27. What command is used to push a Docker image to a Google Cloud Artifact repository?
   - Answer: docker push northamerica-northeast2-docker.pkg.dev/cloud-computing-project-415318/docker-rep/my-nginx-hello-world:latest
---
28. What is the primary role of 'service-b' in the microservices architecture described in the document?
   - Answer: Backend processing
---
29. What command line is used to tag the Docker image `service-a` before pushing it to the repository?
   - Answer: docker tag service-a:latest northamerica-northeast2-docker.pkg.dev/cloud-computing-project-415318/docker-rep/service-a:latest
---
30. Which type of Kubernetes service is described as allowing pods within the cluster to communicate using the service name as a DNS name?
   - Answer: ClusterIP
---
31. What API version is used for the Kubernetes deployment of service-a?
   - Answer: apps/v1
---
32. What is the containerPort specified for the service-a container in its Kubernetes deployment?
   - Answer: 8080
---
33. How does Kubernetes' Node Anti-Affinity enhance the resilience of the system?
   - Answer: By spreading pods across different nodes or fault domains to increase availability and fault tolerance.
---
34. What is the purpose of the `kubectl get svc` command in Kubernetes?
   - Answer: It lists all services in the cluster and shows their configuration details.
---
35. What command would you use to see the external IP and port of the service-a-balancer?
   - Answer: kubectl get svc service-a-balancer
---
36. What is the primary communication method between service-a and service-b in the microservices example from the document?
   - Answer: RESTful API calls
---
37. In what programming language are the microservices (service-a and service-b) implemented as described in the Dockerfiles?
   - Answer: Python
---
38. What environmental variable is defined in both service-a and service-b Dockerfiles?
   - Answer: NAME World
---
39. How is the Docker image for service-a built, as specified in the document?
   - Answer: By using the command docker build -t service-a:latest .
---
40. Which Kubernetes command retrieves details about all running pods in the cluster, including their IP addresses?
   - Answer: kubectl get pods -o wide
