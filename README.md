# FlakyAether
WIP: Nix Based Hypervisor


**v1 (theoretical) scope:**

* **NixOS guests** (images from derivations)
* **Networking** (libvirt networks/bridges, idempotent)
* **Storage** (pools/volumes, qcow2 overlays)
* **3rd-party guests** — *define the VM, not the inside* (point at existing qcow2/iso)
* **PCIe Passtrough**
