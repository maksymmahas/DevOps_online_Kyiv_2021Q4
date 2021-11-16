# DevOps_online_Kyiv_2021Q4

# PART 1. HYPERVISORS
### 1.What are the most popular hypervisors for infrastructure virtualization?
I think the most popular hypervisors for virtualization are Hyper-V and VMware.

### 2.Briefly describe the main differences of the most popular hypervisors.
The most expensive solution today is VMware, Hyper-V is cheaper.
When calculating the cost of a virtualization system, in addition to the hypervisor itself, you need to take into account the cost of software licenses installed on virtual machines. From this vantage point, Hyper-V will provide additional savings over VMware.
In hyper-converged solutions, Hyper-V is significantly cheaper.
The VMware solution implements a fault tolerance mechanism, while the Microsoft solution does not yet.
VMware has a better VDI implementation, but Hyper-V is cheaper to set up VDI.
The Hyper-V solution is less demanding on the hardware side.
In the case of using Hyper-V, the organization of storage will cost less than VMware.
VMware has dedicated tools for balancing loads across host resources; Hyper-V does not.
With System Center Virtual Machine Manager in Hyper-V, you can create private clouds as well as simple server virtualization projects.
### PART 2. WORK WITH VIRTUALBOX

### 1. created VM and installed Ubuntu
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/79a23131c6e9ef1b6826ce364b594ef3-full.jpg)

### 2. cloned an existing VM1 by creating a VM2
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/85f034f445012895d3a3150473c776c4-full.jpg)

### 3. created a group of 2 VMs
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/09c9f9c787d09ed692a3cce11dfeea5a-full.jpg)

### 4. formed a branched tree of snapshots
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/f9ab82dce87c38ff4972e457c89739bc-full.jpg)

### 5. imported VM from *.ova file
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/15ae492457d6c8deb071299ee5eea45d-full.jpg)

### 6. configured the USB
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/a38345b60b8dbfac8d688246de38754a-full.jpg)

### 7. configured a shared folder
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/1a55a02506e62760f828543e47f877a9-full.jpg)

### 8. configured and checked the connections VMs
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/6ca70775294daea03ca141035c875996-full.jpg)

# PART 3. WORK WITH VAGRANT

### 1. created my folder
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/80968c822626e70b32be535fb231de01-full.jpg)

### 2. initialized the environment with the default Vagrant box
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/65b2e55d924c18f40043d272f281371a-full.jpg)

### 3. ran vagrant up
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/6dac1fac533a155e9625246b324e5531-full.jpg)

### 4. connected to the VM using PuTTY
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/8caa11f5abb8653dea25d40e68ed407d-full.jpg)

### 5. recorded the date
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/83da834ad547594e49515e32f9016e3c-full.jpg)

### 6. stopped and deleted VM
![photo](https://cdn1.savepice.ru/uploads/2021/11/16/f30820cabea30de5d882c612b3879cc7-full.jpg)
