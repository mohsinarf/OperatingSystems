## What does an operating system do?
- Memory management
- I/O management
- CPU Scheduling
- Communications
- Multitasking/ programming
---
## What is an operating systems?
 Special layer of software that provides application software access to hardware resources
- Convenient abstraction of complex hardware devices
- Protected access to shared resources
- Security and authentication
- Communication
---
## Virtualization of the Machine
Operating system basically abstract all the hardware resources for other software applications
- Processors -> Threads
- Memory -> Address space
- Storage -> File System
- Network -> socket
![[Virtualizing the machine.png]]
---
## What is process?
**A process consists of :**
- Address space
- One or more threads of control executing in that address space
- Additional system state associated with it
	- Open Files
	- open sockets
	- .....

![[Process.png]]
## Protection Boundary

 - Prevents one process access the resources of another resources
- Manage protection, isolation, and sharing of resources  
- Fault segmentation error -> [[1-1up.pdf#page=32&selection=21,0,21,21|1-1up, page 32]]

![[ProtectionBoundary.png]]

## What is an Operating System?

![[Pasted image 20240416112506.png]]