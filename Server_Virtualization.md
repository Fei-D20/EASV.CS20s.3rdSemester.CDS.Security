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
  - [Application provisioning](应用程序布建, Application provisioning is an infrastructure management solution that helps administrators create customized application configurations called packages.), maintenance, [high availability](高可靠性) and [disaster recovery](损害恢复).
- Security
  - Keep on separate servers.
  - Separate servers do not pose a risk to each other.
  - Especially VM are owned by [mutually](交互的) untrusting users.

## Hypervisor

### [Hypervisor](虚拟机管理器)

#### The role of the hypervisor

- Sit between VM and the hardware.
- Divides a single physical server for multiple OS [to interact with](相互交流) the [underlying hardware](底层硬件).

