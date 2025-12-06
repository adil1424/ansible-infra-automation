# Ansible Infrastructure Automation

This repository contains Ansible playbooks and roles for automating Linux system administration tasks across enterprise environments.

## 📌 What This Repository Includes

### 🔹 Linux Server Hardening
- SSH configuration
- Firewall rules
- PAM & password policies
- Auditd configuration

### 🔹 Server Provisioning
- Package installation
- User/group creation
- NTP, DNS, Time sync setup

### 🔹 Docker / Kubernetes / OpenShift Setup
- Install Docker CE
- Install container runtime
- Prepare Linux node for Kubernetes

### 🔹 Patch Management
- Automated OS updates
- Patch verification logs
- Reboot handling

---

## 📁 Repository Structure
ansible-infra-automation/
│── inventories/
│ ├── prod
│ └── dev
│
│── playbooks/
│ ├── harden-linux.yml
│ ├── install-docker.yml
│ ├── patch-servers.yml
│ └── k8s-node-setup.yml
│
│── roles/
│ ├── linux_hardening/
│ ├── docker_install/
│ └── k8s_setup/
│
└── README.md



---

## 🚀 How to Run
ansible-playbook -i inventories/dev playbooks/harden-linux.yml


---

## 🔧 Tools Used
- Ansible
- YAML
- RHEL / Oracle Linux / Ubuntu
- Docker, Kubernetes prerequisites

---

## 👤 Author
Adil — Linux & Platform Engineer  





