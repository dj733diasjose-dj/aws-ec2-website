# 🌐 AWS EC2 Website Project

This is my first AWS EC2 project, where I deployed a simple HTML website on an Amazon Linux 2023 instance using Apache Web Server.

---

## 🚀 Live Website
👉 [View Live Site](http://65.0.71.150/)

---

## 🖼️ Preview
Here’s what the website looks like:

![Live Website Screenshot](website-screenshot.png)

---

## 🛠️ Technologies Used
- **Amazon EC2 (Amazon Linux 2023)**
- **Apache HTTP Server**
- **HTML**

---

# 🌐 AWS EC2 Website Project

This is my first AWS EC2 project, where I deployed a simple HTML website on an Amazon Linux 2023 instance using Apache Web Server.

---

## 🚀 Live Website
👉 [View Live Site](http://65.0.71.150/)

---

## 🖼️ Preview
Here’s what the website looks like:

![Live Website Screenshot](website-screenshot.png)

---

## 🛠️ Technologies Used
- **Amazon EC2 (Amazon Linux 2023)**
- **Apache HTTP Server**
- **HTML**

---

## 📋 Deployment Steps
1. Created and launched an EC2 instance on AWS.
2. Connected via SSH using my key pair (`dias-keypair1.pem`).
3. Installed Apache web server using:
   ```bash
   sudo dnf update -y
   sudo dnf install httpd -y
   sudo systemctl start httpd
   sudo systemctl enable httpd
