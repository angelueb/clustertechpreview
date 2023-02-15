#Summary of node's roles and hardware

##Roles

###Master
In our case, this role includes:

* Cluster control and management
* Provision and orchestration
* Login
* Job and resource management
* Job submition

###Compute

Nodes with this role actually run the jobs assigned by SLURM. There are specific nodes for CPU and for GPGPU computing.

###Storage

In our case, it provides the shared storage resources that contain user related data (home) and immediate computing jobs data (scratch)

##Hardware summary

*Node name: avicenna
**Cluster role: Master
**CPU: AMD Epyc
***Cores/Threads (total): 16/32
**RAM: 128GB
**Network links
***BMC (VHIR)
***External Acess (VHIR)
***Internal

*Node Name: c01
**Cluster role: Compute
***Type: CPU
**CPU: AMD Epyc x2
***Cores/Threads (total): 32/64
**RAM: 512GB
**Network links
***BMC (VHIR)
***Internal

*Node Name: g01
**Cluster role: Compute
***Type: GPGPU
**CPU: AMD Epyc x2
***Cores/Threads (total): 24
**GPU: Ampere x 2 (24GB VRAM)
**RAM: 512GB
**Network links
***BMC (VHIR)
***Internal
