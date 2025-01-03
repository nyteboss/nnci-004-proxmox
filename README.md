# NNCI-004-PROXMOX

This repository contains the configuration and scripts for the Proxmox VE host NNCI-004-PROXMOX.

## System Information

* **Hostname:** NNCI-004-PROXMOX
* **Proxmox VE version:** 8.3.0
* **Kernel:** 6.8.12-4-pve
* **Network:**
    * Wired: eno1 (DHCP)
    * Wi-Fi: wlp2s0 (disabled)
    * Bridge: vmbr0 (192.168.2.1/24)

## Configuration

* **`/etc/network/interfaces`:**  [See the file in this repository](/etc/network/interfaces)
* **Firewall:**  Currently using iptables (rules to be defined)
* **Storage:**  Local storage (to be expanded with Ceph or other solutions)
* **Backups:**  To be configured with Proxmox Backup Server (PBS)

## Scripts

* **`vm-create.sh`:**  (To be created) Script to automate VM creation.
* **`container-deploy.sh`:** (To be created) Script to automate LXC container deployment.

## To-Do

* **Security hardening:** Implement firewall rules, secure SSH access, and configure fail2ban.
* **Monitoring:** Set up Prometheus and Grafana for monitoring and visualization.
* **Backup and recovery:** Configure Proxmox Backup Server (PBS) and create backup schedules.
* **Automation:** Develop Ansible playbooks for automated deployment and configuration.
* **Documentation:**  Expand this README with more detailed information and instructions.

## Contributing

Feel free to contribute to this repository by submitting pull requests or opening issues.

## License

This repository is licensed under the MIT License.
