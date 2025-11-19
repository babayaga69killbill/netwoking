# Networks & Cloud Computing

## 📚 Table of Contents

### 1. [Virtualization Basics](docs/01-virtualization-basics.md)
* **Interfaces:** TUN vs. TAP
* **Isolation:** Veth Pairs
* **Segmentation:** VLANs

### 2. [Switching & Overlay Networks](docs/02-switching-routing.md)
* **Virtual Switching:** Open vSwitch (OVS) vs. Linux Bridge
* **Tunneling:** VXLAN (Virtual Extensible LAN)

### 3. [Kubernetes Networking (CNI)](docs/03-kubernetes-networking.md)
* **The Flow:** Pod → Veth → Bridge → CNI
* **Plugins:** Flannel vs. Cilium (eBPF)

### 4. [System Architecture & Performance](docs/04-system-architecture.md)
* **Data Flow:** User Space vs. Kernel Space
* **Optimization:** Zero Copy vs. Packet Copy

---

## 🚀 Quick Summary

| Concept | Layer | Key Use Case |
|:--- |:--- |:--- |
| **TUN** | Layer 3 | VPNs (OpenVPN, WireGuard), IP tunneling |
| **TAP** | Layer 2 | VM Bridging, mimicking physical Ethernet |
| **VXLAN** | L2 over L3 | Large-scale cloud overlays (16M+ IDs) |
| **eBPF** | Kernel | High-performance packet filtering (Cilium) |


