#aws-linux-web-server-project
Deployed a web server on AWS EC2 using Amazon Linux. Installed and configured Apache web server to host a custom HTML webpage accessible over the internet.

🚀 AWS EC2 Web Server Project

📌 Project Overview

This project demonstrates how to deploy a basic web server on AWS using EC2. A Linux-based server was launched and configured to host a custom HTML webpage accessible over the internet.

---

🛠️ Technologies Used

* AWS EC2
* Amazon Linux
* Apache (httpd) Web Server
* HTML

---

⚙️ What I Did

* Launched an EC2 instance using Amazon Linux
* Configured Security Groups to allow SSH (port 22) and HTTP (port 80)
* Connected to the server using SSH
* Installed and configured Apache web server
* Created and hosted a custom HTML webpage
* Verified website access via public IP

---

🌐 How It Works

1. User enters the EC2 Public IP in browser
2. Request goes through Internet Gateway
3. Security Group allows HTTP (port 80)
4. Apache web server responds with hosted webpage

---

📷 Output

Successfully hosted a webpage on AWS EC2 instance using Apache.

---

🎯 Key Learnings

* Basics of AWS EC2 and server deployment
* Linux commands and package installation using yum
* Web server setup and configuration
* Networking concepts (ports, public access, security groups)

---

🚀 Future Improvements

* Add Load Balancer and Auto Scaling
* Deploy using Terraform (Infrastructure as Code)
* Use domain name with Route 53
* Enable HTTPS using SSL certificate

---
