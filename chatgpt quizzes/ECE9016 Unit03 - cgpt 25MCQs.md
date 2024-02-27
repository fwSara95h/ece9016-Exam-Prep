Here are 25 MCQs based on "Containerization and Virtualization," along with an answer key at the end:

1. Virtualization allows for:
   - A) Running multiple operating systems on the same hardware
   - B) Increasing the physical hardware capacity
   - C) Directly enhancing network security
   - D) Decreasing application performance
   ---
2. The primary difference between VMs and Containers is:
   - A) VMs require an operating system, while Containers do not
   - B) Containers require a hypervisor, while VMs do not
   - C) VMs encapsulate the entire operating system, while Containers share the host OS kernel
   - D) Containers are suitable for data persistence, while VMs are not
   ---
3. Docker is used for:
   - A) Creating virtual machines
   - B) Provisioning physical servers
   - C) Containerization and application packaging
   - D) Direct hardware virtualization
   ---
4. A hypervisor is:
   - A) A type of container
   - B) Software that manages virtual machines
   - C) A cloud computing service model
   - D) A network management tool
   ---
5. Which of the following is a characteristic of microservices architecture?
   - A) Monolithic application deployment
   - B) Single technology stack for all services
   - C) Independently deployable services
   - D) Unified data storage for all services
   ---
6. Port forwarding in Docker is used to:
   - A) Increase container security
   - B) Disable all network interfaces
   - C) Allow external access to services running in a container
   - D) Connect containers to a virtual private network
   ---
7. Kubernetes is:
   - A) A type of VM
   - B) A containerization platform like Docker
   - C) An orchestration tool for managing containerized applications
   - D) A cloud service model
   ---
8. Docker Images are:
   - A) Mutable entities that change over time
   - B) Built at runtime when a container is instantiated
   - C) Immutable templates used to create containers
   - D) The same as Docker containers
   ---
9. Which network driver isolates containers’ network stack entirely from the Docker host?
   - A) Bridge
   - B) Overlay
   - C) Host
   - D) None
   ---
10. What does a Dockerfile specify?
    - A) Instructions to compile application source code
    - B) The virtual machine settings
    - C) The operating system to be installed in the container
    - D) Instructions for building a Docker image
    ---
11. The main advantage of using a container over a VM is:
    - A) Stronger isolation
    - B) More secure for sensitive tasks
    - C) Better performance and resource efficiency
    - D) Ability to run different operating systems
    ---
12. A bare-metal hypervisor:
    - A) Runs within a host operating system
    - B) Requires a host OS to manage VMs
    - C) Runs directly on the host's hardware to manage VMs
    - D) Is a type of container runtime environment
    ---
13. The primary use case of Docker Volumes is:
    - A) To increase the container’s processing power
    - B) To manage network configurations
    - C) For data persistence and sharing between containers
    - D) To isolate container workloads
    ---
14. The command to create a Docker container from an image is:
    - A) docker create
    - B) docker run
    - C) docker build
    - D) docker start
    ---
15. The bridge network in Docker:
    - A) Disables all networking for a container
    - B) Directly connects a container to the host's network
    - C) Allows containers to communicate with each other on the same Docker host
    - D) Is used for running containers without network isolation
    ---
16. Which statement about Docker Swarm is true?
    - A) It's a containerization technology
    - B) It's a Docker image registry
    - C) It's an orchestration tool for managing multiple containers
    - D) It's used to build Docker images
    ---
17. Containers are best suited for:
    - A) Legacy application support requiring specific OS versions
    - B) Applications requiring direct access to physical hardware
    - C) Microservices and dynamic, scalable applications
    - D) Situations where data persistence is not required
    ---
18. What does the Docker command `docker pull` do?
    - A) Removes an image from the local storage
    - B) Creates a new Docker container
    - C) Downloads an image or a repository from a registry
    - D) Updates an existing image
    ---
19. The main benefit of using named volumes in Docker is:
    - A) Direct mapping of a host file system to a container
    - B) Persistent data storage across container rebuilds
    - C) Temporary storage for sensitive information
    - D) Data encryption and security
    ---
20. Which of the following is NOT a feature of container orchestration?
    - A) Automatic container placement
    - B) Manual scaling of containers
    - C) Health monitoring of containers
    - D) Load balancing between containers
    ---
21. Docker Compose is used for:
    - A) Single-container app deployment
    - B) Defining and running multi-container Docker applications
    - C) Container scaling and orchestration
    - D) Managing the lifecycle of a single container
    ---
22. The process of moving an application from a development environment into a Docker container is known as:
    - A) Virtualization
    - B) Containerization
    - C) Orchestration
    - D) Consolidation
    ---
23. Which type of hypervisor would be most appropriate for a cloud computing environment?
    - A) Type 1: Bare-metal hypervisor
    - B) Type 2: Hosted hypervisor
    - C) Type 3: Container-based hypervisor
    - D) There is no such classification
    ---
24. A Dockerfile `FROM` instruction is used to:
    - A) Specify the base image for the subsequent instructions
    - B) Define the command to run when the container starts
    - C) Set the environment variables within the container
    - D) Copy files from the host to the container
    ---
25. What is the main purpose of Docker Hub?
    - A) To host Docker containers
    - B) To provide a centralized resource for Docker image discovery and distribution
    - C) To automatically manage and scale Docker containers
    - D) To secure Docker containers and images

---

**Answer Key:**
1. A
2. C
3. C
4. B
5. C
6. C
7. C
8. C
9. D
10. D
11. C
12. C
13. C
14. B
15. C
16. C
17. C
18. C
19. B
20. B
21. B
22. B
23. A
24. A
25. B
