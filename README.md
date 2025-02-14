# 🔌 Penetration Testing Environment Setup

## 📖 Introduction
This project provides a **step-by-step guide** to set up a **Penetration Testing Environment** on a **Linux-based system** (Kali Linux or Ubuntu).  
It covers the installation and configuration of essential tools for penetration testing, such as **Postman**, **Git**, **Docker**, **Go**, **jwt_tool**, **Kiterunner**, **Arjun**, and **OWASP ZAP**.

### 🌟 What is Penetration Testing?
**Penetration Testing** is a cybersecurity practice where a tester attempts to exploit vulnerabilities in a system, network, or application to identify weaknesses.  
This project sets up the tools required to carry out security testing and vulnerability assessments in a network or system environment.

---

## 💡 Project Overview
This project guides you through the installation and configuration of the following tools:
- **Postman** for API testing.
- **Git** for version control.
- **Docker** for container management.
- **Go (Golang)** for programming and building tools.
- **jwt_tool** for JWT (JSON Web Token) manipulation.
- **Kiterunner** for automated subdomain enumeration.
- **Arjun** for parameter brute-forcing.
- **OWASP ZAP** for vulnerability scanning.

---

## 🛠️ Features & Implementations

### 🔹 **Postman Setup**
✔ Installs Postman for API testing.  
✔ Creates a symlink to easily run Postman from the terminal.

### 🔹 **Git Installation**
✔ Installs Git for version control.

### 🔹 **Docker Installation**
✔ Installs Docker and Docker Compose for managing containers.

### 🔹 **Go Installation**
✔ Installs Go programming language for developing security tools.

### 🔹 **jwt_tool Setup**
✔ Creates a Python virtual environment for jwt_tool.  
✔ Installs the required dependencies for JWT testing.

### 🔹 **Kiterunner Setup**
✔ Clones and builds Kiterunner for automated subdomain enumeration.  
✔ Creates a symlink for easy tool execution.

### 🔹 **Arjun Setup**
✔ Creates a Python virtual environment for Arjun.  
✔ Installs Arjun for brute-forcing HTTP request parameters.

### 🔹 **OWASP ZAP Installation**
✔ Installs OWASP ZAP for web application vulnerability scanning.

---

## 📂 Files in This Repository
- 📄 `README.md` - **Instructions** for setting up the penetration testing environment.
- 📄 `setup.sh` - **Shell script** to automate the installation process.

---

## 🚀 Getting Started  

### 🔧 **How to Install and Setup the Environment**

1️⃣ **Install Dependencies and Tools**  
Follow the instructions in the README to install each tool step by step. Below are the key commands to install various tools:

#### Postman Installation
```bash
sudo wget https://dl.pstmn.io/download/latest/linux64 -O postman-linux-x64.tar.gz
sudo tar -xvzf postman-linux-x64.tar.gz -C /opt
sudo ln -s /opt/Postman/Postman /usr/bin/postman
postman
