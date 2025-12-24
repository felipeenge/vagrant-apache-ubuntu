```sh
# Vagrant Apache Ubuntu Provisioning

This project is a Junior-level DevOps portfolio project that demonstrates how to automatically provision a Linux environment using Vagrant and Shell scripting, applying Infrastructure as Code (IaC) concepts.

The project sets up an Ubuntu virtual machine, installs and configures the Apache Web Server, and deploys a static website automatically.

---

## 🛠️ Technologies Used

- Vagrant
- VirtualBox
- Ubuntu 18.04 (bionic64)
- Apache2
- Shell Script (Provisioning)

---

## 🎯 Project Goals

- Practice Infrastructure as Code (IaC)
- Learn automated environment provisioning
- Understand basic Linux service management
- Automate web server setup and deployment
- Build a practical DevOps portfolio project

---

## 📌 What This Project Does

- Creates an Ubuntu VM using Vagrant
- Configures a private network with a static IP
- Automatically installs required packages:
  - Apache2
  - Wget
  - Unzip
- Downloads and deploys a static website template
- Starts and enables the Apache service

All steps are executed automatically using `vagrant up`.

---

## 🌐 Network Configuration

- VM private IP: `192.168.75.77`
- Access the website at: 192.168.75.77


---

## 🚀 How to Run the Project

### Prerequisites
- VirtualBox installed
- Vagrant installed
- Git (optional)

### Steps


```bash
git clone https://github.com/felipeenge/vagrant-apache-ubuntu.git
cd vagrant-apache-ubuntu
vagrant up

After provisioning, open your browser and access:
http://192.168.75.77

Re-run Provisioning
vagrant provision

Or reload the VM and provision again:
vagrant reload --provision

Stop or Destroy the Environment
Stop the VM:
vagrant halt

Destroy the VM:
vagrant destroy
```
