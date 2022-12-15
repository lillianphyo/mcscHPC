# Characteristics of Distributed System   
## Resource sharing   
### pros   
hardware resources are shared for reduction in cost and convenience.
data consistency between compilers and libraries. exchange information between databaes. cooperative work as group ware.   
### challenge   
resource management polices and methods.   
security.   
   
## Heterogeneity & Openness   
### pros   
different networks, computer hardware, operating systems, programming languages.   
new components can be easily integrated via standarized interface.   
### challenge   
standardization.   
bandwidth for large network.   
performance for larger workload.   
   
## Concurrency   
### pros   
concurrency reduces the latency and increases the throughput.    
### challenge   
because of concurrent execution take place on different components running on multiple machine, concurrent control techiques may be challenging. It directly effect to system responsiveness and resource allocation. overloading.
data lost.   
   
## Scalability   
### pros   
can esaily extend nodes insted of upgrading single one. by this way, higher demand workload can manage easily.
### challenge   
handling timing problems with caching and data replication.   
   
## Fault Tolerance   
### pros   
increase the availability of services.   
program recovery via the procress group.   
network is redundant.   
### challenge   
nodes can fail. Therefore, hardware need redundancy and software need recovery.   
   
## Transparency   
### pros   
   
### challenge   
   
# Key characteristics of distributed systems   
Resource sharing   
Openess   
Concurrency   
Scalability   
Fault tolerance   
Transparency   
   
# Key design goals   
High performance   
Reliability   
Scalability   
Consistency   
Security   
   
# Basic design issues   
naming   
communications   
software structure   
workload allocation   
consistency maintenance   
   
# Naming   
communication identifier   
name service   
contextual resolution of name   
name mapping   
pure names vs names with meaning   
   
# Communication   
## Reasons for communicating:   
transfer of data   
synchronization   
   
## Methods of communications   
message passing - send and receive primitives   
synchronous or asynchronous   
blocking or non-blocking   
mechanisms of message passing - channels, sockets, ports   
client-server communication model   
group multicast communication model   
   
# Workload Allocation   
Workstation-server model   
Processor pool model   
Shared-memory multiprocessor   
   
# Consistency maintenance   
Update consistency - changes must be atomic   
   
Replication consistency - data must be consistent   
   
Cache consistency (aka cache coherency)   
- client hoarding of partial resources for local use   
- usefulness depends on the principal of locality   
   
Failure consistency - recovery via rollback   
   
Clock consistency - use of timestamping and logical clocks   
   
User interface consistency - action vs processing delay, delays < 0.1 second required   
   
# User Requirements   
Functionality   
Reconfigurability   
Quality of Service   
   
# Functionality   
As a minimum:   
Distributed system should at least provide the function of a single computer   
Improvement:   
- Sharing of resources - hardware   
- Ultilization of distributed resources for parallel processing and fault tolerance   
Cooperative working environments   
   
Migration paths from single computer to distributed system   
1. adapt existing operating system   
2. move to a new system designed for distributed systems   
3. emulation of old system on new system (most practical)   
   
# Reconfigurability
Short-term changes   
Failed process or component   
Computational load shifted   
Caching and process migration (reduction of network overhead)   
Medium to long-term evolution   
New machines   
New services   
Changed roles of machines   
Changed resources on existing machines   
   
# Quality of Service (QOS)   
User needs guarantees   
Performance   
Reliability   
Availability   
Security   


