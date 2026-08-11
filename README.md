# Proxmox VE CLI Helper Tools (`pmtls`)

A collection of interactive command-line utilities and Python scripts designed to simplify management, backup, and resource monitoring for Proxmox Virtual Environment (PVE) hosts.

## 🌟 Features

* **`pmtls`**: Central interactive TUI menu to launch any tool.
* **`backup`**: Advanced vzdump wrapper to list, create (single or batch with notes), and safely manage VM/LXC backups.
* **`pve`**: Quick state management for VMs (Start, Reboot, Graceful Shutdown with automatic forced fallback).
* **`pvesize`**: Detailed real-time breakdown of Host RAM, Swap, and Proxmox Storage pools.
* **`vmdisk`**: Deep internal disk space inspector for running VMs via QEMU Guest Agent.

---

## 🚀 One-Line Installation

Run the following command directly on your Proxmox host as `root`:

curl -sSL https://raw.githubusercontent.com/vryabushkin-alt/proxmox/refs/heads/main/pvetools_en_0.1.0 | bash
