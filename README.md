# 🚀 Uptime Kuma EaaC Setup

> **Environment as Code (EaaC)** enables an easy setup of Uptime Kuma on an Ubuntu virtual machine using Vagrant 🐢 and Docker 🐳 in VirtualBox 📦.  
> Quickly deploy a reliable uptime monitoring solution with minimal effort!

## 🛠️ Requirements

- VirtualBox
- Vagrant

## 🔧 Usage

### Clone the Repository
```bash
git clone https://github.com/cyberllloner/Uptime-Kuma-EaaC-Setup.git
cd Uptime-Kuma-EaaC-Setup
```

### Add the Vagrant Box
```bash
vagrant box add bento/ubuntu-22.04
```

### ⚠️ DNS Notice
> A custom public DNS is set in `script.sh` to bypass some restrictions.  
> You can remove this line or use your preferred DNS.

### Start the Setup
```bash
vagrant up
```

### Wait for Setup to Finish  
You can access **Uptime Kuma** at:  
[localhost:3001](http://localhost:3001)

## 📄 License

This project is licensed under the **MIT License**.
