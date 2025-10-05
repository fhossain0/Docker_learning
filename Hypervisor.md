Difference between hypervisor and docker 
1. Hypervisor (VM-based virtualization)
Virtualizes hardware to create full virtual machines.
Each VM has its own OS (guest OS) on top of the hypervisor.
Heavyweight: VMs take more disk space, memory, and CPU.
Example: VMware ESXi, Hyper-V, VirtualBox.
Analogy: Like building multiple full houses (VMs) on a single land (physical server), each with its own plumbing and electricity (OS).

3. Docker (Container-based virtualization)
Virtualizes the operating system, not the hardware.
Containers share the host OS kernel, so they are lighter and start faster.
More efficient for running apps, but cannot run a completely different OS inside.
Example: Docker, Podman.
Analogy: Like renting rooms in a single house (host OS) where everyone shares the same utilities but can decorate and use the space independently.
