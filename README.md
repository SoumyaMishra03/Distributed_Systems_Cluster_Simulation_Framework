

# Distributed Systems Cluster Simulation Framework

Team Members:  
- Soumya Ranjan Mishra (PES2UG22CS571)  
- Suhas Karamalaputti (PES2UG22CS590)  
- Shuklav Reddy (PES2UG22CS557)  
- Soham Praveen Salunke (PES2UG22CS561)  
- S K Hitha Sree (PES2UG22CS559)  

---

## Project Overview  
This project aims to develop a lightweight, simulation-based system that mimics core Kubernetes cluster management functionalities. It creates a simplified yet comprehensive platform for showcasing key distributed computing concepts such as resource allocation, fault tolerance, and system recovery.

---

## Problem Statement  
Design and implement a distributed systems simulation framework featuring:  
- **API Server**: A centralized control unit for node management, pod scheduling, and health monitoring.  
- **Cluster Nodes**: Virtualized computing units that periodically send heartbeat signals to the API Server.  
- **Pods**: Deployable units simulated on nodes, which require specific CPU resources.

---

## Objectives  
1. Implement a **Node Manager** for tracking and managing nodes.  
2. Develop a **Pod Scheduler** to allocate resources efficiently.  
3. Create a **Health Monitor** for detecting node failures and initiating recovery actions.  
4. Provide a **CLI/Web Interface** for cluster operations.

---

## Weekly Milestones  
### Week 1  
- Implement the base API Server and Node Manager functionality.  
- Develop the feature to add nodes with specified CPU cores (launching Docker containers).  

### Week 2  
- Implement the Pod Scheduler and Health Monitor with heartbeat processing for failure detection.  
- Enable pod launching and automatic scheduling based on CPU resource requirements.  

### Week 3  
- Develop functionality to list all nodes along with their health status.  
- Conduct system testing and finalize project documentation.

---

## Key Deliverables  
1. Node addition process and cluster management.  
2. Efficient pod scheduling across nodes.  
3. Node health monitoring and recovery during failures.  
4. Node health status listing via CLI/Web Interface.

---

## Technology Stack  
- **Docker**: For simulating nodes.  
- **Flask or Node.js**: For implementing the API Server.  
- **Scheduling Algorithms**: First-Fit, Best-Fit, Worst-Fit for pod scheduling.  

---

## Setup Instructions  
1. Clone this repository to your local machine.  
2. Ensure Docker is installed and running.  
3. Start the API Server by executing the appropriate script.  
4. Use the CLI/Web Interface to interact with the system.

---

## Contributors  
- Soumya Ranjan Mishra (Project Lead, Node Manager Implementation)  
- Suhas Karamaputti (Pod Scheduler Development)  
- Shuklav Reddy (API Server Architecture)  
- Soham Praveen Salunke (Health Monitoring and Recovery Mechanisms)  
- S K Hitha Sree (CLI/Web Interface Design)  

