# ☁️ Cloud DevOps Automation (Ansible)

This repository contains **Ansible playbooks and roles** to automate the setup of a complete **Cloud / DevOps development environment**.  
It is designed to quickly provision tools, runtimes, and configurations required for modern DevOps workflows.

---

## 📁 Repository Structure

```text
.
├── roles/                     # Ansible roles
├── README.md                  # Project documentation
├── custom.yml                 # Custom configuration playbook
├── docker.yml                 # Docker installation & setup
├── dockercompose.yml          # Docker Compose setup
├── full.yml                   # Full environment setup playbook
├── fusuma.yml                 # Fusuma configuration
├── git.yml                    # Git installation & config
├── jhipster.yml               # JHipster setup
├── jhipster-contributors.yml  # JHipster contributor tools
├── kubernetes.yml             # Kubernetes tools (kubectl, etc.)
├── maven.yml                  # Maven installation
├── node.yml                   # Node.js setup
├── openjdk8.yml               # OpenJDK 8 installation
├── openjdk11.yml              # OpenJDK 11 installation
├── tilix.yml                  # Tilix terminal setup
├── tools.yml                  # Common DevOps tools
├── yarn.yml                   # Yarn package manager
└── zsh.yml                    # Zsh + shell customization

## 🚀 What This Project Does

✔ Automates DevOps environment setup
✔ Installs popular DevOps & cloud tools
✔ Reduces manual system configuration
✔ Uses Ansible YAML playbooks
✔ Ideal for DevOps engineers, cloud learners, and system admins

## 🧰 Tools & Technologies Covered

🐳 Docker & Docker Compose
☸ Kubernetes (kubectl & related tools)
🧪 Maven
🟢 Node.js & Yarn
☕ OpenJDK 8 & 11
🔧 Git
🐚 Zsh & Tilix
🚀 JHipster
⚙️ Common DevOps utilities

## 📌 Prerequisites

- Linux-based system (Ubuntu recommended)
- Ansible installed

```bash
sudo apt update
sudo apt install ansible -y
ansible-playbook docker.yml
ansible-playbook full.yml
```

💡 You can modify playbooks as per your system requirements.

## 🎯 Who Is This For?
- Aspiring DevOps Engineers & Infrastructure learners
- Developers setting up local environments
- Anyone tired of manual installations 😄

## 📜 License
This project is open-source and free to use for learning and personal projects.

##🤝 Contributions
- Contributions, improvements, and suggestions are welcome!
- Feel free to fork the repo and raise a PR.

## ✨ Author
Amrit Srivastava
Cloud & DevOps Enthusiast 🚀
