# Linux Apache Web Server Setup

## Project Overview
This project demonstrates the installation and configuration of Apache Web Server on a Linux system. It also includes firewall configuration using UFW and version control using Git.

## Technologies Used
- Linux (Ubuntu Server)
- Apache HTTP Server
- UFW Firewall
- Git

## Features
- Installed and configured Apache Web Server
- Hosted a static website
- Configured UFW firewall to allow HTTP and HTTPS traffic
- Used Git for version control
- Monitored Apache logs for troubleshooting

## Commands Used

Install Apache:
sudo apt install apache2 -y

Allow HTTP:
sudo ufw allow 80

Allow HTTPS:
sudo ufw allow 443

Check Apache Status:
sudo systemctl status apache2

## Logs Location
- /var/log/apache2/access.log
- /var/log/apache2/error.log

## Author
Krityanjay V Prajapati
