1. What is the primary purpose of virtualization in cloud computing?
   - A) To create physical hardware replicas
   - B) To create virtual versions of resources like servers and networks
   - C) To increase the physical space in data centers
   - D) To reduce software efficiency
---
2. What does a Virtual Machine (VM) simulate?
   - A) A physical networking system
   - B) An actual operating system only
   - C) A complete hardware system
   - D) A single software application
---
3. Which of the following is a core characteristic of VMs?
   - A) Dependency on physical hardware
   - B) Lack of isolation from other VMs
   - C) Ability to run multiple OS on the same physical hardware
   - D) Reduced flexibility compared to physical machines
---
4. What is the role of a Hypervisor in virtualization?
   - A) To manage digital marketing strategies
   - B) To allocate physical resources to VMs
   - C) To increase the cost of computing resources
   - D) To decrease server performance
---
5. What distinguishes Hosted hypervisors from Bare-metal hypervisors?
   - A) Hosted run on a conventional operating system
   - B) Bare-metal are less secure
   - C) Hosted do not support multiple VMs
   - D) Bare-metal directly manage cloud services
---
6. Which is NOT a common use of VMs?
   - A) Server consolidation
   - B) Enhancing physical server speed
   - C) Development environments
   - D) Legacy application support
---
7. What defines Containers in cloud computing?
   - A) Lightweight executable units that encapsulate an application and its dependencies
   - B) Heavyweight systems that require their own OS
   - C) Tools for hardware virtualization
   - D) Data encryption methods
---
8. How do Containers differ from VMs in terms of system architecture?
   - A) Containers require a separate OS for each instance
   - B) Containers share the host system’s kernel
   - C) Containers use more resources than VMs
   - D) Containers cannot run simultaneously on a single host
---
9. Which of the following is a key advantage of containerization?
   - A) Increased dependency on the host OS
   - B) Reduced portability across environments
   - C) Rapid deployment and scaling
   - D) Higher resource consumption
---
10. What is Docker primarily used for?
    - A) Creating encrypted network tunnels
    - B) Developing and running applications in containers
    - C) Monitoring cloud resource usage
    - D) Virtualizing operating systems
---
11. What type of network is the default when you run a Docker container without specifying a network?
    - A) Host
    - B) None
    - C) Bridge
    - D) Custom
---
12. What is the main function of Docker Compose?
    - A) For defining and running multi-container Docker applications
    - B) To create new Docker images
    - C) Managing virtual machine instances
    - D) Encrypting container data
---
13. Which of the following is NOT a type of Docker volume?
    - A) Named Volumes
    - B) Bind Mounts
    - C) Shared Volumes
    - D) tmpfs Mounts
---
14. How do Containers ensure isolation and security?
    - A) By using dedicated physical hardware for each container
    - B) Through process-level isolation mechanisms
    - C) By preventing the execution of multiple containers on a single host
    - D) Through external firewalls only
---
15. What Docker command is used to create a new container?
    - A) docker start
    - B) docker pull
    - C) docker create
    - D) docker commit
---
16. Which environment variable settings prevent Python from writing .pyc files to disk?
    - A) PYTHONDONTWRITEBYTECODE and PYTHONUNBUFFERED
    - B) PYTHONWRITEBYTECODE and PYTHONBUFFERED
    - C) WRITEBYTECODE and UNBUFFEREDPYTHON
    - D) PYTHONFILES and WRITECODE
---
17. In Docker, what does the -p flag in docker run command specify?
    - A) Priority of the container
    - B) CPU percentage allocation
    - C) Port mapping between the host and the container
    - D) The number of processors to use
---
18. What is the main advantage of Docker's layered architecture for images?
    - A) Increases the size of the images for better security
    - B) Allows sharing layers between images to reduce storage space
    - C) Prevents containers from sharingthe OS
    - D) Allows faster image downloads by sharing layers
---
19. What does a Dockerfile define?
    - A) Network configurations for a Docker container
    - B) Instructions for building a Docker image
    - C) The runtime environment for the Docker daemon
    - D) Security policies for Docker containers
---
20. In container orchestration, what role does Docker Swarm play?
    - A) A tool for continuous integration and continuous deployment
    - B) A native clustering tool for Docker containers
    - C) A security scanner for Docker images
    - D) A logging and monitoring solution for containers
---
21. What is the purpose of Docker Volumes?
    - A) To optimize container startup time
    - B) To provide persistent storage for containers
    - C) To manage container versions
    - D) To reduce the size of Docker images
---
22. How does the Bridge network operate in Docker?
    - A) Isolates the container from the host's network
    - B) Connects containers to the external internet
    - C) Enables direct communication between containers on the same host
    - D) Assigns a public IP address to each container
---
23. What is the result of using the Docker command 'docker run -d --name web_container -p 80:80 nginx'?
    - A) It creates and starts an Nginx container named 'web_container' in detached mode
    - B) It stops and removes a container named 'web_container'
    - C) It connects the 'web_container' to a new network
    - D) It updates the Nginx image to the latest version
---
24. Which Dockerfile instruction is used to set environment variables within the container?
    - A) WORKDIR
    - B) ADD
    - C) ENV
    - D) VOLUME
---
25. What is the significance of the Docker 'EXPOSE' instruction in a Dockerfile?
    - A) It changes the container's base image
    - B) It compiles the application source code
    - C) It sets the container's time zone
    - D) It informs Docker that the container listens on specified network ports

---
26. What is the purpose of Dockerfile in Docker technology?
   - A) To manage container runtime
   - B) To automate container creation
   - C) To configure network settings
   - D) To monitor container performance
---
27. What command is used to create a Docker image from a Dockerfile?
   - A) docker pull
   - B) docker run
   - C) docker build
   - D) docker create
---
28. Which of the following is NOT a standard network in Docker?
   - A) Bridge
   - B) Host
   - C) Direct
   - D) None
---
29. In Docker, what does the 'docker run' command do?
   - A) Builds a new Docker image
   - B) Creates a new Docker container
   - C) Lists all Docker containers
   - D) Stops a running Docker container
---
30. What is the primary function of Docker Compose?
   - A) Container orchestration
   - B) Image creation
   - C) Network configuration
   - D) Volume management
---
31. What Docker command is used to stop a running container?
   - A) docker pause
   - B) docker stop
   - C) docker exit
   - D) docker terminate
---
32. What type of Docker volume persists data even if the container is deleted?
   - A) Ephemeral volume
   - B) Named volume
   - C) Temporary volume
   - D) Shared volume
---
33. How does Docker achieve container isolation?
   - A) By using virtual machines
   - B) By employing namespaces and cgroups
   - C) Through application-level security
   - D) By isolating the host operating system
---
34. What is the main advantage of using Docker in microservices architecture?
   - A) Increased monolithic integration
   - B) Enhanced communication between services
   - C) Isolation and independent deployment
   - D) Uniform operating systems across services
---
35. Which command is used to list all Docker containers?
   - A) docker list all
   - B) docker container list
   - C) docker ps
   - D) docker containers show
---
36. In Docker networking, what does the 'bridge' network enable?
   - A) Internet access to containers
   - B) Private communication between containers on the same host
   - C) Public IP assignment to each container
   - D) Direct host-to-container networking
---
37. What is the result of using 'docker volume create' command?
   - A) Initializes a new Docker container
   - B) Creates a new Docker network
   - C) Generates a new named volume
   - D) Builds a new Docker image
---
38. Which Docker command removes unused data?
   - A) docker clean
   - B) docker system prune
   - C) docker remove unused
   - D) docker delete data
---
39. What is the role of a Docker daemon?
   - A) To execute Docker commands directly
   - B) To manage, create, and monitor Docker containers
   - C) To connect Docker containers to networks
   - D) To compile Docker images from source code
---
40. What is the purpose of the Docker client?
   - A) To provide a graphical interface for Docker
   - B) To issue commands to the Docker daemon
   - C) To store Docker images
   - D) To automate container deployment
---
41. Which of the following is true about Docker images?
   - A) They are mutable and change frequently
   - B) They include the Docker daemon
   - C) They are built layer by layer for efficiency
   - D) They can only be stored locally
---
42. How does the 'tmpfs' mount type in Docker differ from other volume types?
   - A) It is stored on disk and persists across container restarts
   - B) It is stored in memory and erased when a container stops
   - C) It allows direct access to the host filesystem
   - D) It is used for permanent storage solutions
---
43. What is the primary benefit of Docker's layered architecture for images?
   - A) Increases image build time
   - B) Reduces storage space by sharing layers between images
   - C) Ensures that all containers have the same base layers
   - D) Allows running multiple operating systems in one container
---
44. Which feature allows Docker containers to run without networking?
   - A) Bridge mode
   - B) Host mode
   - C) None mode
   - D) Network disable mode
---
45. How do Docker containers access external networks?
   - A) By default, through the host network interface
   - B) Only via virtual private networks (VPNs)
   - C) Using a direct connection bypassing the host system
   - D) Containers cannot access external networks

46. What Docker command is used to inspect the details of a specific container?
   - A) docker inspect
   - B) docker details
   - C) docker check
   - D) docker view
---
47. What is the main difference between Docker's 'COPY' and 'ADD' instructions in a Dockerfile?
   - A) 'COPY' supports network resource addition, 'ADD' does not
   - B) 'ADD' can unpack compressed files, 'COPY' cannot
   - C) 'COPY' creates new container layers, 'ADD' does not
   - D) 'ADD' is deprecated, 'COPY' is recommended
---
48. Which Dockerfile instruction is used to set the container's working directory?
   - A) SET
   - B) WORKDIR
   - C) CD
   - D) DIR
---
49. What is the purpose of the Docker 'CMD' instruction?
   - A) To compile the application
   - B) To set environment variables
   - C) To define the default command to run in the container
   - D) To copy files into the container
---
50. In Docker, what does the '-d' flag specify when running a container?
   - A) Debug mode
   - B) Detached mode
   - C) Development mode
   - D) Directory mode
---
51. What defines a Docker container's lifecycle start phase?
   - A) Initialization
   - B) Creation
   - C) Execution
   - D) Deployment
---
52. How does Docker improve application delivery in DevOps practices?
   - A) By slowing down deployment
   - B) By standardizing environment settings
   - C) By increasing manual intervention
   - D) By reducing scalability
---
53. What is a significant benefit of using Docker for CI/CD pipelines?
   - A) Reduces consistency
   - B) Increases build times
   - C) Enhances portability and efficiency
   - D) Requires more hardware
---
54. When is the 'docker stop' command necessary?
   - A) Before creating a Docker image
   - B) After a Docker build is complete
   - C) To end a running Docker container
   - D) To start a Docker container
---
55. What is achieved by setting the 'PYTHONUNBUFFERED' environment variable in a Dockerfile?
   - A) Python programs write byte code to disk
   - B) Ensures Python output is logged immediately
   - C) Disables Python within the container
   - D) Buffers all Python output to memory
---
56. How is data persistence achieved in Docker containers?
   - A) By saving data within the container's file system
   - B) Using external storage volumes
   - C) By committing changes to the container's image
   - D) Through network storage only
---
57. What is the main reason to use Docker in microservices architecture?
   - A) To increase monolithic dependencies
   - B) To facilitate isolated and independent service scaling
   - C) To centralize all services in one container
   - D) To eliminate the need for continuous integration
---
58. What does 'docker volume rm' command do?
   - A) Removes a specified Docker volume
   - B) Restarts a Docker volume
   - C) Creates a new Docker volume
   - D) Inspects a Docker volume
---
59. Why would you use Docker's 'tmpfs' mounts?
   - A) To store permanent data
   - B) To keep data strictly in host memory
   - C) For long-term storage solutions
   - D) To increase the container's disk space
---
60. What is Docker Swarm used for?
   - A) Single-container management
   - B) Image building
   - C) Cluster and orchestration management
   - D) Network customization

---
61. What is the key advantage of using named volumes in Docker?
   - A) Direct access to host hardware
   - B) Persistence of data across container restarts
   - C) Temporary storage for sensitive data
   - D) Automated data backup to cloud services
---
62. Which Docker command is used to list all networks?
   - A) docker network ls
   - B) docker list networks
   - C) docker show networks
   - D) docker networks all
---
63. How is a Docker container removed?
   - A) docker delete container
   - B) docker rm container
   - C) docker erase container
   - D) docker container remove
---
64. What command is used to attach a Docker volume to a container?
   - A) docker volume attach
   - B) docker run -v volume
   - C) docker add volume
   - D) docker volume add
---
65. In Docker, what does the 'docker ps -a' command show?
   - A) All active Docker processes
   - B) All available Docker images
   - C) All Docker containers, both running and stopped
   - D) All Docker networks
---
66. What type of Docker volume is stored in the host system's memory only?
   - A) Named Volumes
   - B) Bind Mounts
   - C) tmpfs Mounts
   - D) Shared Volumes
---
67. What is the primary use of Docker Compose?
   - A) To combine Docker images
   - B) To start and stop individual containers
   - C) To define and run multi-container Docker applications
   - D) To manage container networks
---
68. Which command pulls an image from a Docker registry?
   - A) docker pull
   - B) docker fetch
   - C) docker get
   - D) docker download
---
69. What is the primary function of Docker Swarm?
   - A) Managing individual containers
   - B) Orchestrating multiple Docker containers
   - C) Building Docker images
   - D) Creating Docker volumes
---
70. What is the main benefit of Docker's port forwarding feature?
   - A) Increases the security of the containers
   - B) Allows containers to use the host's network settings
   - C) Enables external access to services running in a container
   - D) Links two containers' networks together

---
---




**Answer Key:**
1. B
2. C
3. C
4. B
5. A
6. B
7. A
8. B
9. C
10. B
11. C
12. A
13. C
14. B
15. C
16. A
17. C
18. B
19. B
20. B
21. B
22. C
23. A
24. C
25. D
26. A
27. B
28. C
29. B
30. A
31. B
32. B
33. C
34. C
35. C
36. B
37. C
38. B
39. B
40. B
41. C
42. B
43. B
44. C
45. A
46. A
47. B
48. B
49. C
50. B
51. B
52. B
53. C
54. C
55. B
56. B
57. B
58. A
59. B
60. C
61. B
62. A
63. B
64. B
65. C
66. C
67. C
68. A
69. B
70. C