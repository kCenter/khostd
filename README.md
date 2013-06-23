khostd
======

Host daemon for KVM hypervisor/ This is daemon that expose REST API interface to facilitate integration with Virtual Datacenter front end application/it will seat on top of libvirt/qemu/ovs and provide simple command to the host like "create a bridge, create a storage, create a VM ..."

Features

    Storage
      - Ceph
        + cephFS
        + RBD
      - Gluster
      - Swift
      - NFS
      - iSCSI
      - LVMoiSCSI
      - LVMoFC
      - ZFS
    
    Networking
      - OVS
        + DVS
      - Native Bridge
    
    VM Lifecycle Management
      - Start
      - Stop
      - Pause
      - Resume
      - Create
      - Destroy
      - Migrate
    
    Backup
      - Snapshot
      - Clone
    
    Compute Resource Management
      - Host Add
      - Host Remove
      - Host Maintenance
      - Host Resource Report
      


