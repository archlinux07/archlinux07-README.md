# 🐧 Linux Administration & Open Source Lab

<p align="center">
  <img src="https://www.linux.org/images/logo-linux.png" alt="Linux Logo" width="180"/>
</p>

<h1 align="center">🐧 Linux Administration Project</h1>

<p align="center">
  <b>Learn • Practice • Automate • Deploy • Manage Linux Systems</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OS-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/Git-GitHub-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Server-NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="NGINX"/>
</p>

---

## 📌 About This Project

This repository is designed for learning and practicing **Linux Administration,
Linux Commands, Shell Scripting, Networking, Git, Web Servers,
System Administration, and DevOps fundamentals**.

The project contains practical examples that can be executed on
Ubuntu, Debian, Fedora, Rocky Linux, AlmaLinux, Arch Linux,
and other Linux distributions.

---

## 🐧 Linux

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/35/Tux.svg"
       alt="Linux Tux"
       width="150"/>
</p>

Linux is an open-source operating system widely used for:

* 🖥️ Desktop computers
* 🗄️ Servers
* ☁️ Cloud computing
* 📦 Containers
* 🌐 Networking
* 🔐 Security
* 🚀 DevOps
* 🤖 Embedded systems
* 🧪 Research and HPC

---

## ✨ Features

* 🐧 Linux fundamentals
* 💻 Linux command-line practice
* 📁 File and directory management
* 👤 User and group administration
* 🔐 File permissions
* 🌐 Network configuration
* 📡 SSH administration
* 📦 Package management
* ⚙️ Process management
* 💾 Disk management
* 🔥 Firewall configuration
* 📝 Bash scripting
* 🌐 Apache and NGINX
* 🔧 Git and GitHub
* ☁️ Cloud deployment basics
* 🐳 Docker fundamentals
* 📊 System monitoring

---

## 🎬 Animated Linux

<p align="center">
  <img src="https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif"
       alt="Coding Animation"
       width="500"/>
</p>

> 💡 Practice Linux every day and build your command-line skills.

---

## 🛠️ Technologies

| Technology | Purpose                     |
| ---------- | --------------------------- |
| 🐧 Linux   | Operating System            |
| 🐚 Bash    | Shell Scripting             |
| 🌐 NGINX   | Web Server                  |
| 🪶 Apache  | Web Server                  |
| 🔧 Git     | Version Control             |
| 🐙 GitHub  | Code Hosting                |
| 🐳 Docker  | Containerization            |
| ☁️ AWS     | Cloud Platform              |
| 🔑 SSH     | Remote Administration       |
| 📦 APT     | Debian Package Manager      |
| 📦 DNF     | Fedora/RHEL Package Manager |

---

## 📂 Project Structure

```text
linux-project/
│
├── README.md
├── commands/
│   ├── basic.sh
│   ├── files.sh
│   ├── users.sh
│   └── network.sh
│
├── scripts/
│   ├── backup.sh
│   ├── monitoring.sh
│   └── cleanup.sh
│
├── nginx/
│   └── nginx.conf
│
├── apache/
│   └── apache.conf
│
├── networking/
│   ├── ip-config.sh
│   └── ssh-config.sh
│
└── docs/
    └── linux-notes.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/linux-project.git
```

### 2️⃣ Enter Directory

```bash
cd linux-project
```

### 3️⃣ Check Files

```bash
ls -la
```

### 4️⃣ Check Linux Version

```bash
cat /etc/os-release
```

---

## 💻 Basic Linux Commands

### 📁 Directory Commands

```bash
pwd
ls
ls -la
cd /var
mkdir test
rmdir test
```

### 📄 File Commands

```bash
touch example.txt
cat example.txt
cp example.txt backup.txt
mv backup.txt document.txt
rm document.txt
```

### 🔎 Search Commands

```bash
find / -name "*.conf"
grep "root" /etc/passwd
which bash
whereis nginx
```

---

## 👤 User Management

Create a user:

```bash
sudo useradd linuxuser
```

Set password:

```bash
sudo passwd linuxuser
```

Create a group:

```bash
sudo groupadd developers
```

Add user to group:

```bash
sudo usermod -aG developers linuxuser
```

Check current user:

```bash
whoami
```

---

## 🔐 Linux Permissions

Check permissions:

```bash
ls -l
```

Change permissions:

```bash
chmod 755 script.sh
```

Change ownership:

```bash
sudo chown user:user example.txt
```

Example permission:

```text
-rwxr-xr-x
```

Meaning:

```text
Owner  = rwx
Group  = r-x
Others = r-x
```

---

## 🌐 Networking

Check IP address:

```bash
ip addr
```

Check routing:

```bash
ip route
```

Test connectivity:

```bash
ping 8.8.8.8
```

Check DNS:

```bash
nslookup google.com
```

Check listening ports:

```bash
ss -tulpn
```

---

## 🔑 SSH

Install SSH server on Ubuntu:

```bash
sudo apt update
sudo apt install openssh-server
```

Start SSH:

```bash
sudo systemctl enable --now ssh
```

Connect to another Linux system:

```bash
ssh username@192.168.1.100
```

---

## 📦 Package Management

### Ubuntu / Debian

```bash
sudo apt update
sudo apt upgrade
sudo apt install nginx
```

Remove package:

```bash
sudo apt remove nginx
```

### Fedora / RHEL

```bash
sudo dnf update
sudo dnf install nginx
```

---

## ⚙️ System Management

Check system status:

```bash
systemctl status
```

Start a service:

```bash
sudo systemctl start nginx
```

Stop a service:

```bash
sudo systemctl stop nginx
```

Enable service at boot:

```bash
sudo systemctl enable nginx
```

---

## 📊 Process Management

Show processes:

```bash
ps aux
```

Interactive monitoring:

```bash
top
```

Better monitoring:

```bash
htop
```

Find process:

```bash
pgrep nginx
```

---

## 💾 Disk Management

Check disk usage:

```bash
df -h
```

Check directory size:

```bash
du -sh /var/log
```

List disks:

```bash
lsblk
```

Check mounted filesystems:

```bash
mount
```

---

## 🌐 NGINX Web Server

Install NGINX:

```bash
sudo apt update
sudo apt install nginx
```

Check status:

```bash
sudo systemctl status nginx
```

Open browser:

```text
http://SERVER-IP
```

Test configuration:

```bash
sudo nginx -t
```

Restart NGINX:

```bash
sudo systemctl restart nginx
```

---

## 🐚 Bash Script Example

Create a script:

```bash
nano system-info.sh
```

Add:

```bash
#!/bin/bash

echo "=========================="
echo " Linux System Information "
echo "=========================="

echo "Hostname: $(hostname)"
echo "User: $(whoami)"
echo "Kernel: $(uname -r)"
echo "Uptime: $(uptime -p)"
echo "Date: $(date)"
```

Make executable:

```bash
chmod +x system-info.sh
```

Run:

```bash
./system-info.sh
```

---

## 🔧 Git Workflow

Configure Git:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Initialize repository:

```bash
git init
```

Check status:

```bash
git status
```

Add files:

```bash
git add .
```

Commit:

```bash
git commit -m "Initial Linux project"
```

Push:

```bash
git push origin main
```

---

## ☁️ Cloud & DevOps

This project can be extended to:

* ☁️ AWS EC2
* ☁️ AWS S3
* ☁️ AWS RDS
* 🐳 Docker
* ☸️ Kubernetes
* 🔄 CI/CD
* 🔧 Jenkins
* 🌐 NGINX
* 🔐 SSH
* 📊 Prometheus
* 📈 Grafana

---

## 🖼️ Linux Desktop

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/af/Ubuntu_logo.svg"
       alt="Ubuntu Logo"
       width="180"/>
  &nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Fedora_logo.svg"
       alt="Fedora Logo"
       width="150"/>
</p>

---

## 🧪 Practice Tasks

Try completing these exercises:

1. Create a Linux user.
2. Create a new group.
3. Configure file permissions.
4. Find large files.
5. Check running processes.
6. Configure SSH.
7. Install NGINX.
8. Host an HTML page.
9. Create a Bash script.
10. Configure Git.
11. Create a GitHub repository.
12. Push Linux scripts to GitHub.
13. Monitor CPU and memory.
14. Check disk usage.
15. Configure a basic firewall.

---

## 📚 Learning Roadmap

```text
Linux Basics
     ↓
File System
     ↓
Users & Permissions
     ↓
Networking
     ↓
SSH
     ↓
Bash Scripting
     ↓
Web Server
     ↓
Git & GitHub
     ↓
Docker
     ↓
Cloud
     ↓
DevOps
```

---

## 🎯 Learning Goals

By completing this project, you should be able to:

* Understand Linux architecture.
* Work confidently in the terminal.
* Manage files and directories.
* Create and manage users.
* Configure permissions.
* Troubleshoot basic networking.
* Manage Linux services.
* Write Bash scripts.
* Configure SSH.
* Deploy a basic web server.
* Use Git and GitHub.
* Understand basic DevOps workflows.

---

## 🤝 Contributing

Contributions are welcome!

```bash
git fork
git clone <repository-url>
git checkout -b feature/new-feature
git add .
git commit -m "Add new feature"
git push origin feature/new-feature
```

Then create a Pull Request.

---

## ⚠️ Important Note

Always test commands carefully, especially commands involving:

```bash
rm
fdisk
parted
mkfs
dd
chmod
chown
systemctl
```

Some commands can permanently modify files, disks, or system configuration.

---

## 📜 License

This project is intended for **educational and learning purposes**.

You may modify and extend the examples for your own Linux,
DevOps, networking, and system-administration practice.

---

## ⭐ Support

If this project helps you learn Linux:

<p align="center">
  ⭐ <b>Star this repository</b> ⭐
</p>

<p align="center">
  🐧 Keep Learning Linux • Keep Practicing • Keep Building 🚀
</p>

---

## 🐧 Final Message

<p align="center">
  <img src="https://media.giphy.com/media/3o7TKMt1VVNkHV2PaE/giphy.gif"
       alt="Linux Terminal Animation"
       width="450"/>
</p>

<h2 align="center">🐧 Linux • Open Source • Automation • DevOps 🚀</h2>

<p align="center">
  <b>Learn it. Practice it. Automate it.</b>
</p>
