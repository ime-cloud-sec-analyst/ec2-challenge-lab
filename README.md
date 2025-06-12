# EC2 Challenge Lab 🚀

This project demonstrates the setup of a secure and functional **Amazon EC2 instance** as part of the AWS re/Start program hands-on lab. The instance is configured to run a basic web server that serves a custom HTML page.

## 🛠️ Lab Objectives

- Create and configure a Virtual Private Cloud (VPC)
- Launch an EC2 instance using Amazon Linux 2023
- Configure security groups to allow:
  - SSH (port 22) from a specific IP or anywhere (lab-specific)
  - HTTP (port 80) to allow web traffic
- Install Apache (httpd) using `yum`
- Deploy a sample web page to `/var/www/html/projects.html`

## ✅ What’s Included

The repository includes screenshots of key setup steps:
- ✅ VPC and subnet configuration
- ✅ EC2 instance creation and running status
- ✅ Security group inbound rules setup
- ✅ System log verification of Apache installation
- ✅ Terminal view of the Linux shell access
- ✅ Screenshot of successful webpage hosted at `/projects.html`

## 📷 Screenshots

This project folder contains visual evidence of:
- EC2 instance creation and status
- Apache (httpd) installation
- HTML file deployment and result
- Security configuration
- VPC layout and routing

## 🔒 Security Note

While 0.0.0.0/0 was used for HTTP and SSH access during the lab for demonstration purposes, this **is not recommended in production**. Always restrict access to known IPs.

## 🌐 Final Web Page Preview

> http://52.39.177.234/projects.html  
(Active only while the EC2 instance is running)

---

Let me know when you're ready, and I can help you commit this or make further updates.
