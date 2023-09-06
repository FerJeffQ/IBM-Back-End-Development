# Components of Cloud Computing: Graded Quiz

1. Each Cloud Region can have multiple Availability Zones. What are Zones?
   
   - Unique physical locations with one or more data centers
   
   - Single shared point of failure
   
   - Geographic area or region where the cloud provider’s infrastructure is clustered
   
   - Standardized containers of computing resources
     
     ```
     Answer:
     - Unique physical locations with one or more data centers
     Explanation:
     - Zones, or Availability Zones, are distinct locations with one or more data centers with power, cooling, and networking resources.
     ```

2. Which of the following is a benefit of virtualization?
   
   - Is secure
   
   - Runs a single operating system
   
   - Increases your downtime
   
   - Cost savings
     
     ```
     Answer:
     - Cost savings
     Explanation:
     - You can run multiple virtual environments from one piece of infrastructure, which means that you can drastically reduce your physical infrastructure footprint.
     ```

3. Which of the following types of Virtual Machine (VM) guarantees resources for future deployments?
   
   - Shared or Public Cloud VMs
   
   - Transient or Spot VMs
   
   - Reserved virtual servers
   
   - Dedicated hosts
     
     ```
     Answer:
     - Reserved virtual servers
     Explanation:
     - Users can reserve specific virtual server instances for guaranteed capacity.
     ```

4. Which of the following is a feature of bare metal servers?
   
   - Rapidly provisioned
   
   - Low cost to use
   
   - Multiple tenants
   
   - High performance and secure
     
     ```
     Answer:
     - High performance and secure
     Explanation:
     - Bare metal servers are dedicated and intended for long-term, high-performance use in highly secure and isolated environments.
     ```

5. Subnets are the main area where security is implemented in the cloud. Which of the following is used to provide security at the virtual instance level in subnets?
   
   - Security Groups or SGs
   
   - Virtual Private Cloud or VPC
   
   - Load Balancers
   
   - Public Gateways
     
     ```
     Answer:
     - Security Groups or SGs
     Explanation:
     -  SGs provide instance-level security.
     ```

6. Which of the following is a benefit of isolation of applications in containers?
- Preventing malicious code in one container from impacting other containers

- Open-sourced runtime engine

- Abstraction from the host operating system

- Repackaged into containers or containerized microservices
  
  ```
  Answer:
  - Preventing malicious code in one container from impacting other containers
  Explanation:
  - The isolation of applications in containers reduces the chance that malicious code in one container will impact other containers or invade the host system.
  ```
7. Which of the following storage types are ephemeral or non-persistent?
   
   - Direct Attached storage
   
   - Block storage
   
   - File storage
   
   - Object storage
     
     ```
     Answer:
     -
     Explanation:
     - 
     ```

8. What makes file storage an ideal solution for scenarios where shared storage is required?
   
   - File storage can be mounted on multiple compute nodes at the same time
   
   - File storage can be mounted from remote storage appliances
   
   - Fast accessibility of file storage over the network
   
   - File storage is mounted to compute nodes via an ethernet network
     
     ```
     Answer:
     -File storage can be mounted on multiple compute nodes at the same time
     Explanation:
     - The ability for File Storage to be mounted to various compute nodes at a time makes it an ideal solution for shared storage requirements.
     ```

9. Which of the following scenarios is best suited for Block Storage?
   
   - Applications that need consistent fast access to the disk, such as databases
   
   - Where workloads do not require fast connectivity to storage
   
   - Low cost is a consideration
   
   - Workloads that need disk sharing between compute nodes
     
     ```
     Answer:
     - Applications that need consistent fast access to the disk, such as databases
     Explanation:
     - Fiber optic networks move traffic at consistently high speeds, making them ideal for applications that need consistent and fast access.
     ```

10. Which of the following is a feature of Object storage?
    
    - Storage is attached to compute nodes using a fiber network
    
    - You can directly use Object Storage without attaching it to a compute node
    
    - Used where fast read and write speeds are necessary
      
      Object Storage can be mounted on multiple compute nodes via an ethernet network
      
      ```
      Answer:
      -You can directly use Object Storage without attaching it to a compute node
      Explanation:
      - You don’t need an underlying compute node to connect to object storage. Instead, you can access it from anywhere using an API. 
      ```


