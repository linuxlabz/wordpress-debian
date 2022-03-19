# Installing WordPress On Debian 11 VPS.. Quick Start Guide

![WebServer](https://netslovers.com/wp-content/uploads/2022/03/wordpress-debian.png)

As described in the above figure, we will use:

We will try to install WordPress CMS on Debian 11 VPS, we will install and configure Nginx as a reverse proxy, Apache as a web server, PHP Packages, and MariaDB database server.

## Web Technology To Use

1. Nginx as a reverse proxy (listen Ports 443, 80)
2. Apache as a web-server (listen Port 81)
3. WordPress CMS Our PHP Web Application
4. MariaDB Database Server

## Configure The Debian 11 VPS/Server

**we will:**

- Update our server.
- Install required packages ( i.e. MariaDB, Nginx, Apache, and PHP ).
- Add The Domain User To The System.
- [Install WP-CLI](./wordpress-wp-cli)
- Install WordPress
- Set WordPress File Permission
- Firewalls for all ports except HTTP(S) and SSH.
- Install fail2bab to harden SSH access.

The Full Articles Are Here: https://netslovers.com/2022/03/19/installing-wordpress-on-debian-11/
