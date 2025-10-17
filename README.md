# 🏠 My Homelab

A self-hosted environment built to learn new tools, technologies, and move towards a more private computing experience.

---

## Overview

This homelab is designed as a learning and experimentation platform for:

* Testing **virtualization and containerization** platforms
* Building a secure **networking environment** with VLANs and firewalls
* Deploying and managing **self-hosted services**
* Exploring **monitoring, alerting, and backup** strategies


---

## Architecture

NETWORK TOPOLOGY HERE

**Components:**
- Compute: Proxmox VE running multiple VMs (with containers)
- Networking: OPNsense firewall, VLAN segmentation, VPN access
- Storage: TrueNAS with ZFS for redundancy and snapshots
- Monitoring: Prometheus + Grafana dashboards for metrics and alerts

---

## Hardware

- Repurposed old custom built PC:
  * Ryzen 7 2700, 8 cores 16 threads
  * 16 GB DDR4 RAM
  * Intel x540 t2 PCIe ethernet card (10 Gbps)
  * 2x used 8TB Western Digital Hard Drives
  * Radeon RX 580 (8GB VRAM)
- Switch:
  * TP-Link 1 Gbps PoE++ Switch
- Access Point:
  * Grandstream GWN 7665 Wifi 6E AP

## Software Stack

- Virtualization: Proxmox VE
- Containerization: Docker
- Networking: OPNsense
- NAS: TrueNAS
- Photo Library: Immich
- More to come as this repo gets expanded :)
