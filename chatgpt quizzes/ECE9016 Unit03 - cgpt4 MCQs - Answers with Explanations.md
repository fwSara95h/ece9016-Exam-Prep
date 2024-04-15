1. What is the primary purpose of virtualization in cloud computing?
   - **Answer: B) To create virtual versions of resources like servers and networks**
   - **Explanation:** Virtualization enables the creation of simulated environments, including virtual servers, storage, and networks, allowing multiple systems to run on the same physical hardware efficiently.

---

2. What does a Virtual Machine (VM) simulate?
   - **Answer: C) A complete hardware system**
   - **Explanation:** A VM simulates a complete hardware system from CPU to network, enabling it to run an operating system and applications like a physical machine.

---

3. Which of the following is a core characteristic of VMs?
   - **Answer: C) Ability to run multiple OS on the same physical hardware**
   - **Explanation:** One of the main features of VMs is their ability to run multiple operating systems simultaneously on the same physical hardware, providing significant flexibility and resource utilization.

---

4. What is the role of a Hypervisor in virtualization?
   - **Answer: B) To allocate physical resources to VMs**
   - **Explanation:** A hypervisor is responsible for managing the virtual environments, including allocating physical resources like CPU, memory, and storage to various VMs.

---

5. What distinguishes Hosted hypervisors from Bare-metal hypervisors?
   - **Answer: A) Hosted run on a conventional operating system**
   - **Explanation:** Hosted hypervisors run on top of an existing operating system, unlike bare-metal hypervisors, which run directly on the hardware and manage the OSes running on the VMs.

---

6. Which is NOT a common use of VMs?
   - **Answer: B) Enhancing physical server speed**
   - **Explanation:** Virtual machines do not inherently enhance the speed of physical servers; they virtualize resources and can lead to better resource allocation but not necessarily higher raw performance.

---

7. What defines Containers in cloud computing?
   - **Answer: A) Lightweight executable units that encapsulate an application and its dependencies**
   - **Explanation:** Containers are lightweight, provide a consistent software environment, and encapsulate an application along with its dependencies, distinct from full virtual machines.

---

8. How do Containers differ from VMs in terms of system architecture?
   - **Answer: B) Containers share the host system’s kernel**
   - **Explanation:** Unlike VMs, which require their own operating system, containers share the host system's kernel, making them more resource-efficient.

---

9. Which of the following is a key advantage of containerization?
   - **Answer: C) Rapid deployment and scaling**
   - **Explanation:** Containerization allows for quick deployment and easy scaling of applications since each container can be rapidly started, stopped, or replicated.

---

10. What is Docker primarily used for?
    - **Answer: B) Developing and running applications in containers**
    - **Explanation:** Docker is a platform used to develop, ship, and run applications inside containers, providing an isolated environment for them.

---

11. What type of network is the default when you run a Docker container without specifying a network?
    - **Answer: C) Bridge**
    - **Explanation:** By default, Docker uses the bridge network which allows containers connected to the same bridge network to communicate, while isolating them from containers on other networks.

---

12. What is the main function of Docker Compose?
    - **Answer: A) For defining and running multi-container Docker applications**
    - **Explanation:** Docker Compose is a tool used to define and manage multi-container applications with Docker, using a YAML file to configure application services.

---

13. Which of the following is NOT a type of Docker volume?
    - **Answer: C) Shared Volumes**
    - **Explanation:** Docker supports named volumes, bind mounts, and tmpfs mounts, but 'shared volumes' is not a recognized type within the Docker platform.

---

14. How do Containers ensure isolation and security?
    - **Answer: B) Through process-level isolation mechanisms**
    - **Explanation:** Containers use various process-level isolation mechanisms such as namespaces and cgroups to ensure that each container is isolated and secure from others.

---

15. What Docker command is used to create a new container?
    - **Answer: C) docker create**
    - **Explanation:** The `docker create` command creates a new container but does not start it. This allows for configuration before the container runs.

---

16. Which environment variable settings prevent Python from writing .pyc files to disk?
    - **Answer: A) PYTHONDONTWRITEBYTECODE and PYTHONUNBUFFERED**
    - **Explanation:** Setting `PYTHONDONTWRITEBYTECODE` prevents Python from writing .pyc files, and `PYTHONUNBUFFERED` forces it to use unbuffered streams.

---

17. In Docker, what does the -p flag in docker run command specify?
    - **Answer: C) Port mapping between the host and the container**
    - **Explanation:** The `-p` flag specifies port mappings, allowing specific ports on the host to be directed to ports in the container.

---

18. What is the main advantage of Docker's layered architecture for images?
    - **Answer: B) Allows sharing layers between images to reduce storage space**
    - **Explanation:** Docker's layered architecture allows multiple images to share the same layers, which can significantly reduce storage space and speed up deployments.

---

19. What does a Dockerfile define?
    - **Answer: B) Instructions for building a Docker image**
    - **Explanation:** A Dockerfile contains a set of instructions used to build a Docker image, specifying the operating environment and the commands to run.

---

20. In container orchestration, what role does Docker Swarm play?
    - **Answer: B) A native clustering tool for Docker containers**
    - **Explanation:** Docker Swarm is a native clustering and scheduling tool for Docker containers, allowing users to manage a cluster of Docker nodes as a single virtual system.

---

21. What is the purpose of Docker Volumes?
    - **Answer: B) To provide persistent storage for containers**
    - **Explanation:** Docker volumes are used to store data in a way that persists beyond the life of a single container, useful for data that needs to remain available.

---

22. How does the Bridge network operate in Docker?
    - **Answer: C) Enables direct communication between containers on the same host**
    - **Explanation:** The bridge network is the default Docker network that allows containers connected to it to communicate with each other while isolating them from other networks.

---

23. What is the result of using the Docker command 'docker run -d --name web_container -p 80:80 nginx'?
    - **Answer: A) It creates and starts an Nginx container named 'web_container' in detached mode**
    - **Explanation:** This command runs an Nginx container in detached mode (background), with port 80 on the host mapped to port 80 in the container, and names it 'web_container'.

---

24. Which Dockerfile instruction is used to set environment variables within the container?
    - **Answer: C) ENV**
    - **Explanation:** The `ENV` instruction in a Dockerfile sets environment variables within the container that can be used by applications running inside it.

---

25. What is the significance of the Docker 'EXPOSE' instruction in a Dockerfile?
   - **Answer: D) It informs Docker that the container listens on specified network ports**
   - **Explanation:** The EXPOSE instruction does not publish the port itself but acts as a way of documenting which ports are intended to be published, making it clear which ports the container will listen on.

---

26. What is the purpose of Dockerfile in Docker technology?
   - **Answer: B) To automate container creation**
   - **Explanation:** A Dockerfile is used to automate the process of creating a Docker container. It contains a set of instructions on how to build a Docker image that can then be run as a container.

---

27. What command is used to create a Docker image from a Dockerfile?
   - **Answer: C) docker build**
   - **Explanation:** The `docker build` command is used to build Docker images from a Dockerfile and a "context" that specifies the set of files located in the specified PATH or URL.

---

28. Which of the following is NOT a standard network in Docker?
   - **Answer: C) Direct**
   - **Explanation:** The standard networks in Docker include bridge, host, and none. 'Direct' is not a recognized standard network type within Docker.

---

29. In Docker, what does the 'docker run' command do?
   - **Answer: B) Creates a new Docker container**
   - **Explanation:** The `docker run` command is used to create a new container from a Docker image and run it. It combines the actions of `docker create` and `docker start`.

---

30. What is the primary function of Docker Compose?
   - **Answer: A) Container orchestration**
   - **Explanation:** Docker Compose is a tool for defining and running multi-container Docker applications. It allows you to configure application services and manage them as a single service.

---

31. What Docker command is used to stop a running container?
   - **Answer: B) docker stop**
   - **Explanation:** The `docker stop` command is used to stop one or more running containers. It sends a SIGTERM, and after a grace period, a SIGKILL.

---

32. What type of Docker volume persists data even if the container is deleted?
   - **Answer: B) Named volume**
   - **Explanation:** Named volumes are designed to persist data, independent of the container lifecycle. Docker manages these volumes by name.

---

33. How does Docker achieve container isolation?
   - **Answer: B) By employing namespaces and cgroups**
   - **Explanation:** Docker uses namespaces to provide the isolated workspace called the container, and cgroups (control groups) to limit and prioritize the resources a container can use.

---

34. What is the main advantage of using Docker in microservices architecture?
   - **Answer: C) Isolation and independent deployment**
   - **Explanation:** Docker facilitates the microservices architecture by allowing each service to be contained in its own container environment, ensuring they can be deployed independently.

---

35. Which command is used to list all Docker containers?
   - **Answer: C) docker ps**
   - **Explanation:** The `docker ps` command lists the currently running containers. With specific flags, it can also list all containers, including those that are stopped.

---

36. In Docker networking, what does the 'bridge' network enable?
   - **Answer: B) Private communication between containers on the same host**
   - **Explanation:** The bridge network allows containers connected to the same bridge network to communicate with each other while isolating them from containers not connected to that bridge.

---

37. What is the result of using 'docker volume create' command?
   - **Answer: C) Generates a new named volume**
   - **Explanation:** The `docker volume create` command is used to create a new named volume that can be attached to containers.

---

38. Which Docker command removes unused data?
   - **Answer: B) docker system prune**
   - **Explanation:** The `docker system prune` command removes unused Docker objects, such as containers, images, and volumes.

---

39. What is the role of a Docker daemon?
   - **Answer: B) To manage, create, and monitor Docker containers**
   - **Explanation:** The Docker daemon is a background process that manages the state of Docker containers and handles the tasks related to building, running, and distributing Docker containers.

---

40. What is the purpose of the Docker client?
   - **Answer: B) To issue commands to the Docker daemon**
   - **Explanation:** The Docker client provides the primary user interface to Docker. It translates user commands into API calls that the Docker daemon can understand.

---

41. Which of the following is true about Docker images?
   - **Answer: C) They are built layer by layer for efficiency**
   - **Explanation:** Docker images are constructed from layers that increase reusability, decrease disk usage, and speed up the docker builds through the use of cache.

---

42. How does the 'tmpfs' mount type in Docker differ from other volume types?
   - **Answer: B) It is stored in memory and erased when a container stops**
   - **Explanation:** The `tmpfs` mount type is stored in the host system’s memory only, and it is not written to the host's filesystem. It is erased when the container stops.

---

43. What is the primary benefit of Docker's layered architecture for images?
   - **Answer: B) Reduces storage space by sharing layers between images**
   - **Explanation:** Docker's layered architecture allows multiple images to reuse the same layers, significantly reducing the storage space required and speeding up image downloads.

---

44. Which feature allows Docker containers to run without networking?
   - **Answer: C) None mode**
   - **Explanation:** The 'none' network mode disables networking for a container. In this mode, the container does not receive an IP address.

---

45. How do Docker containers access external networks?
   - **Answer: A) By default, through the host network interface**
   - **Explanation:** By default, Docker uses the host machine's network connection to allow containers to access external networks unless configured to use a different networking mode.

---

46. What Docker command is used to inspect the details of a specific container?
   - **Answer: A) docker inspect**
   - **Explanation:** The `docker inspect` command provides detailed information about Docker objects, including containers, images, volumes, or networks.

---

47. What is the main difference between Docker's 'COPY' and 'ADD' instructions in a Dockerfile?
   - **Answer: B) 'ADD' can unpack compressed files, 'COPY' cannot**
   - **Explanation:** 'ADD' has the capability to handle local-only tar files and remote URLs and unpack them into the destination directory, whereas 'COPY' is a straightforward file and folders copying command.

---

48. Which Dockerfile instruction is used to set the container's working directory?
   - **Answer: B) WORKDIR**
   - **Explanation:** The `WORKDIR` instruction in a Dockerfile is used to set the working directory for any `RUN`, `CMD`, `ENTRYPOINT`, `COPY`, and `ADD` instructions that follow it in the Dockerfile.

---

49. What is the purpose of the Docker 'CMD' instruction?
   - **Answer: C) To define the default command to run in the container**
   - **Explanation:** The CMD instruction in a Dockerfile specifies the default command to execute when the container starts. It can be overridden by providing a different command when starting the container.

---

50. In Docker, what does the '-d' flag specify when running a container?
   - **Answer: B) Detached mode**
   - **Explanation:** The `-d` flag runs the container in detached mode, meaning it runs in the background and does not block the console from which it was started.

---

51. What defines a Docker container's lifecycle start phase?
   - **Answer: B) Creation**
   - **Explanation:** The start phase of a Docker container's lifecycle begins with its creation, which establishes the container from an image before it moves to execution.

---

52. How does Docker improve application delivery in DevOps practices?
   - **Answer: B) By standardizing environment settings**
   - **Explanation:** Docker containers provide a consistent environment for development, testing, and production, reducing the "it works on my machine" syndrome and streamlining the CI/CD pipeline.

---

53. What is a significant benefit of using Docker for CI/CD pipelines?
   - **Answer: C) Enhances portability and efficiency**
   - **Explanation:** Docker containers are portable across different environments and provide a consistent runtime environment, making them ideal for continuous integration and continuous deployment pipelines.

---

54. When is the 'docker stop' command necessary?
   - **Answer: C) To end a running Docker container**
   - **Explanation:** The `docker stop` command is used to send a SIGTERM followed by a SIGKILL to gracefully stop a running container.

---

55. What is achieved by setting the 'PYTHONUNBUFFERED' environment variable in a Dockerfile?
   - **Answer: B) Ensures Python output is logged immediately**
   - **Explanation:** Setting `PYTHONUNBUFFERED` to a truthy value in a Docker container ensures that the Python output is sent directly to the terminal without being buffered, which is useful for logging and debugging in real time.

---

56. How is data persistence achieved in Docker containers?
   - **Answer: B) Using external storage volumes**
   - **Explanation:** Data persistence beyond the lifecycle of a single container is achieved by mounting external storage volumes to containers, allowing data to remain after containers are stopped or deleted.

---

57. What is the main reason to use Docker in microservices architecture?
   - **Answer: B) To facilitate isolated and independent service scaling**
   - **Explanation:** Docker provides an ideal environment for microservices by enabling independent scaling and management of small, isolated services that make up a larger application.

---

58. What does 'docker volume rm' command do?
   - **Answer: A) Removes a specified Docker volume**
   - **Explanation:** The `docker volume rm` command is used to remove one or more volumes. It can only remove unused volumes unless the force option is used.

---

59. Why would you use Docker's 'tmpfs' mounts?
   - **Answer: B) To keep data strictly in host memory**
   - **Explanation:** `tmpfs` mounts are used to store data temporarily in the host system's RAM, ensuring fast data access and automatic data deletion when the container stops.

---

60. What is Docker Swarm used for?
   - **Answer: C) Cluster and orchestration management**
   - **Explanation:** Docker Swarm is used for clustering and managing multiple Docker containers, allowing them to be deployed and managed across multiple host machines as a single virtual system.

---

61. What is the key advantage of using named volumes in Docker?
   - **Answer: B) Persistence of data across container restarts**
   - **Explanation:** Named volumes provide a way to store container data persistently across container restarts and even beyond the life of containers, maintaining data across deployments.

---

62. Which Docker command is used to list all networks?
   - **Answer: A) docker network ls**
   - **Explanation:** The `docker network ls` command lists all networks created by Docker, providing visibility into how containers are networked.

---

63. How is a Docker container removed?
   - **Answer: B) docker rm container**
   - **Explanation:** The `docker rm` command is used to remove one or more stopped containers from the host, freeing up resources.

---

64. What command is used to attach a Docker volume to a container?
   - **Answer: B) docker run -v volume**
   - **Explanation:** When running a container, the `-v` or `--volume` flag followed by the volume identifier is used to attach a volume to a container.

---

65. In Docker, what does the 'docker ps -a' command show?
   - **Answer: C) All Docker containers, both running and stopped**
   - **Explanation:** The `docker ps -a` command lists all Docker containers on the system, regardless of their state, providing a comprehensive view of the containers managed by Docker.

---

66. What type of Docker volume is stored in the host system's memory only?
   - **Answer: C) tmpfs Mounts**
   - **Explanation:** `tmpfs` mounts are a type of Docker volume that stores data in the host system's RAM, and this data is erased when the container is stopped.

---

67. What is the primary use of Docker Compose?
   - **Answer: C) To define and run multi-container Docker applications**
   - **Explanation:** Docker Compose is primarily used to configure and run applications consisting of multiple Docker containers, simplifying the management of complex container setups.

---

68. Which command pulls an image from a Docker registry?
   - **Answer: A) docker pull**
   - **Explanation:** The `docker pull` command is used to fetch an image from a Docker registry and save it to the local system, allowing it to be used to create containers.

---

69. What is the primary function of Docker Swarm?
   - **Answer: B) Orchestrating multiple Docker containers**
   - **Explanation:** Docker Swarm provides native clustering functionality for Docker containers, helping orchestrate and manage multiple containers as if they were a single service.

---

70. What is the main benefit of Docker's port forwarding feature?
   - **Answer: C) Enables external access to services running in a container**
   - **Explanation:** Port forwarding in Docker is used to map ports from the host to the container, allowing external clients to access services running inside the container on specified ports.
