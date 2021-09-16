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
  -  [^Application provisioning] maintenance, [^high availability] and [^disaster recovery]
- Security
  - Keep on separate servers.
  - Separate servers do not pose a risk to each other.
  - Especially VM are owned by [^mutually] untrusting users.



###### 注解:

[^Application provisioning]: 应用程序布建, Application provisioning is an infrastructure management solution that helps administrators create customized application configurations called packages.
[^high availablity]:高可靠性
[^disaster recovery]:损害恢复
[^mutually]:交互的









## Hypervisor

### The role of the hypervisor[^hypervisor]

- Sit between VM and the hardware.
- Divides a single physical server for multiple OS [^to interact with] the [^underlying hardware].





[^hypervisor]: 虚拟机管理器 (Virtual Machine Monitor / VMM)
[^to interact with]: 
[^underlying hardware]:相互交流

