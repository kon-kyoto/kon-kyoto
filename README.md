# kon-kyoto

[![K3s](https://img.shields.io/badge/k3s-1.31+-FFC61A?logo=rancher&logoColor=black)](https://k3s.io/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-1.31+-326CE5?logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![KVM](https://img.shields.io/badge/KVM-QEMU-660066?logo=qemu&logoColor=white)](https://www.linux-kvm.org/)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-24.04-E95420?logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?logo=arch-linux&logoColor=white)](https://archlinux.org/)
[![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white)](https://python.org/)
[![Docker](https://img.shields.io/badge/Docker-24.0+-2496ED?logo=docker&logoColor=white)](https://docker.com/)
[![Flask](https://img.shields.io/badge/Flask-2.3+-000000?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> "I don't write bad code — I create learning opportunities from mistakes."

**kon-kyoto** is my personal ecosystem of tools for security, automation, and deep system understanding.

This repository is the entry point. Here I collect documentation, concepts, and the connecting links between my projects.

---

## 🔥 Currently used stack (live)

| Technology | Purpose |
|------------|---------|
| **K3s** | Lightweight Kubernetes on a test bench (1 master + 2 workers) |
| **KVM/QEMU** | Cluster node virtualization |
| **Ubuntu 24.04 LTS** | Base OS for all VMs |
| **Arch + Hyprland** | Host system for pentesting and development |
| **Python + scipy** | Traffic analysis (`wifi_sentinel`) |
| **inotify + syslog** | Process monitoring daemon (`logwatch`) |

---

## 🧩 Projects

### 🛠️ Tools

| Project | Purpose | Current stack |
|---------|---------|----------------|
| `wifi_sentinel` | Passive traffic profiler | Python + scipy |
| `logwatch` | Process monitoring daemon (inotify + syslog) | Makefile, Python, tests |

### ⚙️ OS Configuration

| Project | Purpose | Current stack |
|---------|---------|----------------|
| `arch_config` | Arch + BlackArch + Hyprland (Wayland) for pentesting | configs, KVM, K3s |

### 📚 Study projects

| Project | Purpose | Current stack |
|---------|---------|----------------|
| `c2bash` | My C knowledge wrapped in bash commands | C, bash, KVM, K3s |
| `microservices_lab` | My microservices app | Docker, nginx, Flask, Python, redis, K3s |

---

## 🧠 Philosophy

> There is black magic. Period.

---

## 📬 Contact

Found a bug? Have an idea? Open an issue. I read them all.  
(I only reply if the bug is amusing.)

---

## 📜 License

MIT. Take it, break it, fix it.
