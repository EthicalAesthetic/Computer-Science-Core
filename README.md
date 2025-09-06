
# Computer Science Core Concepts 

This repository provides an advanced overview of core computer science concepts, including in-depth explanations, technical diagrams, and references for further research. It is suitable for advanced learners, interview preparation, and professionals seeking a deeper understanding.

---

## Table of Contents
1. [Hardware](#1-hardware)
2. [Software](#2-software)
3. [Server](#3-server)
4. [Computation / Processor / CPU](#4-computation--processor--cpu)
5. [RAM](#5-ram)
6. [ROM / Storage](#6-rom--storage)
7. [Network](#7-network)
8. [Operating System](#8-operating-system)
9. [X-86](#9-x-86)
10. [ARM](#10-arm)
11. [RISC V](#11-risc-v)
12. [CISC](#12-cisc)
13. [CLI](#13-cli)
14. [Linux](#14-linux)
15. [Ubuntu](#15-ubuntu)
16. [Terminal](#16-terminal)
17. [GUI](#17-gui)
18. [Cloud Computing](#18-cloud-computing)
19. [AWS](#19-aws)
20. [Open Source](#20-open-source)
21. [Kernel](#21-kernel)
22. [AI](#22-ai)
23. [Directory / Folder](#23-directory--folder)

[Algorithms](#algorithms)<br>
[Mathematical Spaces](#mathematical-spaces)<br>
[NP-Hard Problems](#np-hard-problems)  <br>
---

# 1. Hardware 

Hardware refers to the physical components of a computer system, including the CPU, RAM, motherboard, storage devices, buses, and peripheral devices. Advanced topics include:
- **Motherboard architecture** (chipsets, buses, expansion slots)
- **CPU sockets and compatibility**
- **Power delivery and thermal management**
- **Peripheral interfaces** (PCIe, USB, SATA, NVMe)

<img src="images/hardware.svg" alt="Hardware Diagram" width="350"/>

# 2. Software
Software includes system software (operating systems, device drivers), application software, and development tools. Advanced concepts:
- **Virtualization and containers**
- **Software architecture patterns** (MVC, microservices)
- **Compiler and interpreter design**
- **Software lifecycle and DevOps**

<img src="images/software.svg" alt="Software Illustration" width="350"/>

# 3. Server
A server is a system that provides resources, data, or services to clients over a network. Advanced server topics:
- **Load balancing and clustering**
- **High availability and failover**
- **Virtualization (hypervisors, containers)**
- **Security (TLS, firewalls, intrusion detection)**

<img src="images/server.svg" alt="Server Icon" width="350"/>

# 4. Computation / Processor / CPU
The CPU (Central Processing Unit) is responsible for executing instructions and performing calculations. Advanced CPU topics:
- **Pipelining, superscalar, and out-of-order execution**
- **Branch prediction and speculative execution**
- **Cache hierarchy (L1, L2, L3)**
- **SIMD, MIMD, and parallelism**
- **Instruction set architectures (ISA)**

<img src="images/cpu.svg" alt="CPU Diagram" width="350"/>

## Processing Units (CPU, GPU, TPU)

### Core Differences
- CPU (Central Processing Unit):
   - Compute Primitive: Scalar (single value).
   - Operation: Parallelized scalar multiplication.
   - Memory Management: Implicitly managed (L1, L2, L3 caches).
- GPU (Graphics Processing Unit):
   - Compute Primitive: Vector (1D array).
   - Operation: Parallelized vector multiplication.
   - Memory Management: Mixed (L1, L2 caches, Shared Memory).
- TPU (Tensor Processing Unit):
   - Compute Primitive: Tensor/Matrix (2D array).
   - Operation: Parallelized matrix multiplication.
   - Memory Management: Explicitly managed (Activation Buffer, Register File).
- Other Processing Hardware
   - APU (Accelerated Processing Unit): CPU and GPU on a single chip.
   - FPGA (Field-Programmable Gate Array): Reconfigurable integrated circuit.
   - AI Accelerators: Specialized hardware for AI workloads.
RISC-V: An open-source instruction set architecture (ISA).

# 5. RAM
Random Access Memory (RAM) is volatile memory used for temporary data storage. Advanced RAM topics:
- **DDR generations (DDR3, DDR4, DDR5)**
- **ECC (Error-Correcting Code) RAM**
- **Memory channels and bandwidth**
- **Latency and timing (CAS, RAS)**

<img src="images/ram.svg" alt="RAM Module" width="350"/>

# 6. ROM / Storage
ROM (Read-Only Memory) stores firmware, while storage devices (HDD, SSD, NVMe, SAN) provide persistent data storage. Advanced storage topics:
- **RAID levels and redundancy**
- **File systems (NTFS, ext4, ZFS, Btrfs)**
- **Storage protocols (SATA, NVMe, SCSI, iSCSI, Fibre Channel)**
- **Wear leveling and TRIM in SSDs**

<img src="images/storage.svg" alt="Storage Devices" width="350"/>

# 7. Network
Networks connect computers and devices to share resources and data. Advanced networking topics:
- **OSI and TCP/IP models (detailed layer functions)**
- **Subnetting, CIDR, and VLANs**
- **Routing protocols (OSPF, BGP, RIP)**
- **Network security (VPN, firewalls, IDS/IPS)**
- **Wireless standards (802.11, WPA3)**
- **SDN (Software Defined Networking)**

<img src="images/network.svg" alt="Network Topology" width="350"/>

**Key Terms:**
- **ISP**: Internet Service Provider
- **IP / Standards**: Internet Protocols (IPv4, IPv6)
- **IPv6**: Newer version of IP addressing
- **APIPA (169.x.x.x)**: Automatic Private IP Addressing
- **Public IP (e.g., 192.168.x.x)**: Routable on the internet
- **Private IP**: Used within local networks
- **Local-Host (127.0.0.1)**: Refers to the local machine
- **LAN**: Local Area Network
- **MAN**: Metropolitan Area Network
- **WAN**: Wide Area Network
- **Internet**: Global network of networks
- **Intranet**: Private network within an organization
- **NIC**: Network Interface Card
- **Router**: Directs data between networks
- **Modem**: Modulates and demodulates signals for internet access
- **MAC Address**: Unique identifier for network interfaces
- **DNS**: Domain Name System, translates domain names to IP addresses
- **Packet**: Unit of data transmitted over a network
- **OSI Layers**: Open Systems Interconnection model, 7 layers for network communication

# 8. Operating System
An operating system (OS) manages hardware, software resources, and provides services for applications. Advanced OS topics:
- **Kernel architectures (monolithic, microkernel, hybrid)**
- **Process scheduling and concurrency**
- **Memory management (paging, segmentation, virtual memory)**
- **File system management and journaling**
- **Security (user permissions, sandboxing, SELinux, AppArmor)**

<img src="images/os.svg" alt="Operating System Logo" width="350"/>

# 9. X-86
x86 is a family of CISC instruction set architectures based on the Intel 8086 CPU. Advanced x86 topics:
- **Protected mode and real mode**
- **SIMD extensions (MMX, SSE, AVX)**
- **Microcode and instruction pipelining**
- **Backward compatibility and legacy support**

<img src="images/x86.svg" alt="x86 Architecture" width="350"/>

# 10. ARM
ARM is a RISC architecture widely used in mobile, embedded, and increasingly server environments. Advanced ARM topics:
- **ARMv8, ARMv9, and TrustZone**
- **Big.LITTLE architecture**
- **Instruction pipelining and out-of-order execution**
- **ARM vs x86 performance and power efficiency**

<img src="images/arm.svg" alt="ARM Architecture" width="350"/>

# 11. RISC V
RISC-V is an open standard RISC instruction set architecture. Advanced RISC-V topics:
- **Custom instruction extensions**
- **Open hardware and ecosystem**
- **RISC-V privilege levels and security**
- **Comparison with ARM and x86**

<img src="images/riscv.svg" alt="RISC V Logo" width="350"/>

# 12. CISC
CISC (Complex Instruction Set Computing) CPUs have many specialized instructions. Advanced CISC topics:
- **Microprogramming**
- **Instruction decoding and execution**
- **CISC vs RISC trade-offs**

<img src="images/cisc.svg" alt="CISC Diagram" width="350"/>

# 13. CLI
The Command Line Interface (CLI) is a text-based interface for interacting with computers. Advanced CLI topics:
- **Shell scripting (Bash, PowerShell, Zsh)**
- **Pipelines, redirection, and process control**
- **Remote access (SSH, SCP, SFTP)**
- **Automation and DevOps workflows**

<img src="images/cli.svg" alt="CLI Example" width="350"/>

# 14. Linux
Linux is an open-source family of Unix-like operating systems. Advanced Linux topics:
- **Kernel compilation and customization**
- **Systemd and init systems**
- **Package management (APT, YUM, Pacman)**
- **Security (SELinux, AppArmor, firewalls)**

<img src="images/linux.svg" alt="Linux Logo" width="350"/>

# 15. Ubuntu
Ubuntu is a popular Linux distribution based on Debian. Advanced Ubuntu topics:
- **LTS vs non-LTS releases**
- **Snap and Flatpak packaging**
- **Server vs desktop editions**
- **Cloud and container deployments**

<img src="images/ubuntu.svg" alt="Ubuntu Logo" width="350"/>

# 16. Terminal
A terminal is a program that provides a CLI for interacting with the OS. Advanced terminal topics:
- **Terminal multiplexers (tmux, screen)**
- **Unicode and encoding support**
- **Custom prompts and themes**
- **Remote terminals and SSH**

<img src="images/terminal.svg" alt="Terminal Window" width="350"/>

# 17. GUI
The Graphical User Interface (GUI) allows users to interact with devices using graphical elements. Advanced GUI topics:
- **GUI frameworks (Qt, GTK, Electron, WPF)**
- **Accessibility and internationalization**
- **Event-driven programming**
- **UI/UX design principles**

<img src="images/gui.svg" alt="GUI Example" width="350"/>

# 18. Cloud Computing
Cloud computing delivers computing services over the internet. Advanced cloud topics:
- **IaaS, PaaS, SaaS models**
- **Cloud orchestration (Kubernetes, Docker Swarm)**
- **Hybrid and multi-cloud architectures**
- **Cloud security and compliance**

<img src="images/cloud.svg" alt="Cloud Computing Concept" width="350"/>

# 19. AWS
Amazon Web Services (AWS) is a leading cloud platform. Advanced AWS topics:
- **EC2, S3, Lambda, and advanced services**
- **Infrastructure as Code (CloudFormation, Terraform)**
- **Security (IAM, KMS, VPC)**
- **Cost optimization and billing**

<img src="images/aws.svg" alt="AWS Logo" width="350"/>

# 20. Open Source
Open source software allows anyone to inspect, modify, and enhance the code. Advanced open source topics:
- **Licensing (GPL, MIT, Apache, BSD)**
- **Community governance and contribution models**
- **Open source security and supply chain**

<img src="images/opensource.svg" alt="Open Source Symbol" width="350"/>

# 21. Kernel
The kernel is the core of an OS, managing resources and hardware-software communication. Advanced kernel topics:
- **Kernel modules and drivers**
- **Process and thread management**
- **Inter-process communication (IPC)**
- **Security and isolation (namespaces, cgroups)**

<img src="images/kernel.svg" alt="Kernel Diagram" width="350"/>

# 22. AI
Artificial Intelligence (AI) simulates human intelligence in machines. Advanced AI topics:
- **Machine learning (supervised, unsupervised, reinforcement)**
- **Deep learning (neural networks, CNNs, RNNs, transformers)**
- **Natural language processing (NLP)**
- **AI ethics and explainability**

<img src="images/ai.svg" alt="AI Concept" width="350"/>

# 23. Directory / Folder
A directory (folder) is an organizational unit in a file system. Advanced directory topics:
- **File system hierarchies (FHS, Windows, macOS)**
- **Permissions and ACLs**
- **Symbolic and hard links**
- **Mount points and network file systems (NFS, SMB)**

<img src="images/directory.svg" alt="Directory Structure" width="350"/>

---

- TensorFlow: An open-source platform for machine learning.
- TPU (Tensor Processing Unit): A hardware accelerator designed by Google to speed up machine learning workloads, especially with TensorFlow.

# Algorithms
   1. Searching
      - Linear Search 
      - Binary Search (Reduce time and space complexity) (Think of worst case scenarios)
   2. Sorting
      - Bubble Sort
      - Selection Sort
      - Insertion Sort
      - Merge Sort
      - Quick Sort
      - Heap Sort
   3. Graphs
      - BFS
      - DFS   
      - Dijkstra's Algorithm
      - A* Search
      - Bellman-Ford Algorithm
   4. Dynamic Algorithms
         - Fibonacci   
         - Knapsack Problem
         - Longest Common Subsequence
         - Coin Change Problem        
   5. Backtracking  
      - N-Queens Problem
6. Greedy Algorithms
   - Activity Selection Problem
   - Huffman Coding
   - Kruskal's Algorithm
   - Prim's Algorithm
7. Travelling Salesman Problem
   8. Scheduling Algorithms
      - Round Robin Scheduling
      - Priority Scheduling
      - Round Robin Scheduling
      - Priority Scheduling
Fast Fourier Transform
   - Image Processing (OpenCV, PIL)
   - Audio Processing (Librosa)
   - Video Processing (MoviePy)
   
# Mathematical Spaces

The following are important types of mathematical spaces used in advanced mathematics and computer science:

- Hilbert space
- Banach space     
- Metric space
- Vector space
Vector space


2^10 = 1024 bits = 1 KB
2^20 = 1024 KB = 1 MB   
2^30 = 1024 MB = 1 GB
2^35 = 2^5 * 2^30 = 32 GB

 
# NP-Hard Problems

NP-hard problems are computational problems for which no efficient solution algorithm is known; solving any NP-hard problem efficiently would solve all problems in NP efficiently. Examples include the Travelling Salesman Problem, Knapsack Problem, and Boolean Satisfiability Problem (SAT).


## RoadMap of 4 Years of College (Focus on applications)

1. operating system
   -Cpu scheduling (round robin - Load balancing)
   -Memory management (RAM, ROM, Virtual memory)
2. DBMS
   - Normalization (1NF, 2NF, 3NF, BCNF)
   - SQL (DDL, DML, DCL, TCL)
3. Computer Networks
    - OSI Model (7 layers)
    - TCP/IP Model (4 layers)
    - Protocols (HTTP, FTP, SMTP, etc.) 
4. system design
   - Scalability (Horizontal, Vertical)
   - Load Balancing (Round Robin, Least Connections, IP Hash)
   - Caching (In-Memory, Distributed)
   - Database Sharding (Horizontal, Vertical)
   - CAP Theorem (Consistency, Availability, Partition Tolerance)
   - Microservices Architecture (Advantages, Challenges)
   - Message Queues (RabbitMQ, Kafka)
   - Content Delivery Networks (CDNs) (How they work, Benefits)
   Upstream 

5. ML (Prolog)40 years ago (fk)
6. Data Science
7. CSA
## GOAL
Padhai Sahi Direction mai <br>
Application ke baare mai sochnna hai<br>
LEARN ABOUT MEMORY FROM C language

1. DAA (design and analysis of algorithm)
2. DS (data structure)
3. Algorithm
4. Complexity (time and space) (Worst case)
5. LDPC (Low Density Parity Check) (APPLICATION)
6. Scheduling(in DBMS)
7. Scoping (Static and Dynamic)
8. What's now after Ceasae Cipher (security)(man in the middle)


## References & Further Reading

- [Wikipedia: Computer Science](https://en.wikipedia.org/wiki/Computer_science)
- [How Computers Work (YouTube)](https://www.youtube.com/watch?v=OAx_6-wdslM)
- [OSI Model Explained](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)
- [AWS Cloud Overview](https://aws.amazon.com/what-is-aws/)
- [Linux Kernel Documentation](https://www.kernel.org/doc/html/latest/)
- [RISC-V International](https://riscv.org/)
- [ARM Developer Resources](https://developer.arm.com/)
- [Open Source Initiative](https://opensource.org/)
- [Stanford CS 140: Operating Systems](https://web.stanford.edu/class/cs140/)
- [MIT 6.824: Distributed Systems](https://pdos.csail.mit.edu/6.824/)

---

---