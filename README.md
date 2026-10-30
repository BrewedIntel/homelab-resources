# Homelab Resources
A curated collection of tools, platforms, hardware ideas, and guides for building and maintaining a homelab.  
Covers virtualization, networking, DNS, automation, monitoring, storage, and self-hosted applications.

---

## Table of Contents
- [Virtualization & Hypervisors](#virtualization--hypervisors)
- [Server OS & Bare-Metal Platforms](#server-os--bare-metal-platforms)
- [Networking, DNS & DHCP](#networking-dns--dhcp)
- [Storage & Backup](#storage--backup)
- [Monitoring & Observability](#monitoring--observability)
- [Automation & Configuration Management](#automation--configuration-management)
- [Self-Hosted Services](#self-hosted-services)
- [Security & Identity](#security--identity)
- [Hardware Ideas](#hardware-ideas)
- [Helpful Homelab Communities](#helpful-homelab-communities)
- [Contributing](#contributing)

---

## Virtualization & Hypervisors

### **Proxmox VE**  
https://www.proxmox.com  
Enterprise-grade virtualization with KVM + LXC containers. Popular for homelabs.

### **VMware ESXi (Free/Legacy)**  
Still widely used in homelabs, though support has shifted.

### **XCP-ng**  
https://xcp-ng.org  
Open-source XenServer alternative with great community support.

### **KVM / virt-manager**  
Native Linux virtualization using libvirt.

---

## Server OS & Bare-Metal Platforms

### **Ubuntu Server**  
https://ubuntu.com  
Stable for Docker, K8s, VMs, and general homelab workloads.

### **Debian Server**  
Lightweight and reliable.

### **TrueNAS Scale / Core**  
https://www.truenas.com  
NAS OS with app catalogs, VMs, and containers.

### **Rocky Linux / AlmaLinux**  
Enterprise-class RHEL alternatives for stable infrastructure.

---

## Networking, DNS & DHCP

### **OPNsense**  
https://opnsense.org  
Firewall, routing, VPN, IDS/IPS.

### **pfSense**  
https://www.pfsense.org  
Open-source router/firewall with a large ecosystem.

### **Ubiquiti UniFi**  
APs, switches, cameras, and gateways for homelabs.

### **MikroTik RouterOS**  
Feature-rich routers with powerful scripting.

### **PowerDNS**  
https://www.powerdns.com  
Authoritative + recursor DNS, supports API-based DDNS.

### **Pi-hole / AdGuard Home**  
Network-wide ad blocking, DNS sinkhole.

### **Kea DHCP**  
Next-gen DHCP server from ISC.

### **LockIP Dynamic DNS**  
https://lockip.net  
Simple DDNS with API keys, ideal for homelab address tracking.

---

## Storage & Backup

### **ZFS**  
Snapshots, replication, and unbeatable data integrity.

### **Ceph**  
Distributed storage for larger homelabs.

### **MinIO**  
https://min.io  
S3-compatible object storage.

### **Syncthing**  
Peer-to-peer file sync.

### **Restic**  
Deduplicated, encrypted backups.

### **Veeam Community Edition**  
Backup for VMs and servers.

---

## Monitoring & Observability

### **Grafana**  
Dashboards for metrics and logs.

### **Prometheus**  
Metrics collection and alerting.

### **Zabbix**  
Enterprise-grade monitoring system.

### **Netdata**  
Instant performance graphs and health monitoring.

### **Uptime Kuma**  
Simple status page + uptime monitoring.

---

## Automation & Configuration Management

### **Ansible**  
Agentless automation ideal for homelabs.

### **Terraform**  
Infrastructure-as-code for cloud and on-prem.

### **SaltStack**  
Powerful orchestration with agents or agentless modes.

### **Docker Compose**  
Lightweight automation for multi-container apps.

---

## Self-Hosted Services

### **Nextcloud**  
Private file storage, calendar, contacts, tasks.

### **Gitea / Forgejo**  
Self-hosted Git service.

### **Jellyfin**  
Media server alternative to Plex.

### **Home Assistant**  
Home automation powerhouse.

### **Bitwarden / Vaultwarden**  
Password management.

### **Portainer**  
Manage Docker and Kubernetes visually.

### **Paperless-NGX**  
Document management and OCR.

---

## Security & Identity

### **Authelia**  
SSO portal with 2FA and identity management.

### **Keycloak**  
Full identity platform for apps and homelabs.

### **Fail2ban**  
SSH/Docker security via log-based banning.

### **CrowdSec**  
Collaborative threat defense for home networks.

---

## Hardware Ideas

### **Small Form Factor (SFF) PCs**  
Cheap and power-efficient homelab nodes.

### **Intel NUC / Minisforum / Beelink**  
Great for Kubernetes clusters or Proxmox nodes.

### **Dell R720 / R730 / R620**  
Common enterprise servers for budget homelabs.

### **Raspberry Pi / ARM boards**  
Lightweight automation or monitoring nodes.

### **Homelab Hardware Price Trackers**  
https://sheley.org/trackers/  
Live used and new prices for drives, RAM, mini PCs, NAS, servers and switches, ranked by $/TB, $/GB or $/port.

---

## Helpful Homelab Communities

### **r/homelab (Reddit)**  
Large community with build logs and guides.

### **ServeTheHome Forums**  
Best hardware-focused homelab community.

### **Homelab Wiki**  
General homelab guidance and documentation.

---

## Contributing
Pull requests with additional tools, build guides, or homelab ideas are welcome.
