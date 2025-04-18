# Hardware

The EIDF Virtual Machine Service (VMS) runs on a number of hypervisors located in EPCCs datacentre.

The service currently has a mixture of hardware node types which host VMs of various [flavours](flavours.md):

- The mcomp nodes which host general flavour VMs are based upon AMD EPYC 7702 CPUs (128 Cores) with 1TB of DRAM
- The hcomp nodes which host capability flavour VMs are based upon 4x Intel Xeon Platinum 8280L CPUs (224 Threads, 112 cores with HT) with 3TB of DRAM
- The GPU nodes which host GPU flavour VMs are based upon 2x Intel Xeon Platinum 8260 CPUs (96 Cores) with 4x Nvidia Tesla V100S 32GB and 1.5TB of DRAM

The specification of the VM flavours are based on subdivisions of this hardware, noting that CPUs are 4x oversubscribed for mcomp nodes (general VM flavours).

Block storage is provided by CephRBD, part of EPCCs Ceph file-system and is used as the VMs main disk. Optionally, [CephFS](sharedfs.md) can be mounted as `/home` or at another location to make sharing data between VMs or other EIDF compute services simpler.
