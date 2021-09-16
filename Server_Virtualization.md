# Server Virtualization

## Server Virtualization

### What is Server Virtualization

- Multiple virtual computer running on a single hardware instance.
- Each virtual computer running individual OS.
- Each virtual machine share physical resources (CPU, memory, etc.)

### What is virtualization use for

- Effective Resource Usage : can be located any where.
- Easy to management : 
  - unused machines only cost disk space.
  - Application provisioning[^1], maintenance, high availability[^2]and disaster recovery[^3]
- Security
  - Keep on separate servers.
  - Separate servers do not pose a risk to each other.
  - Especially VM are owned by mutually[^4] untrusting users.



[^1]:应用程序布建, Application provisioning is an infrastructure management solution that helps administrators create customized application configurations called packages.
[^2]:高可靠性
[^3]:损害恢复
[^4]:交互的









## Hypervisor

### [Hypervisor](虚拟机管理器)

#### The role of the hypervisor

- Sit between VM and the hardware.
- Divides a single physical server for multiple OS [to interact with](相互交流) the [underlying hardware](底层硬件).

