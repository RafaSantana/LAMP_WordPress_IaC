# Infra as Code with Vagrant and Ansible

## Project/lab of my IaC learning

The goal is to mount a server [Wordpress](https://wordpress.org/) using [Vagrant](https://www.vagrantup.com) and [Ansible](https://www.ansible.com), the application will be on one server and the Database on anotherserver.

---

### **Servers caracteristcs**

#### Server 1 - **Wordpress**

* PHP – Version 7.4
  * Installation of modules for communication and manipulation with Ansible, DB MySQL and Apache

* Apache – Latest version
  * Change setting for apache fetch index in Wordpress directory

* Wordpress - Latest version  
  * Send the directory to the Apache folder  
  * Change Wordpress installation configuration file
  * Set up Wordpress to communicate with DB

### Server 2 - **MySQL**

* MySQL - Latest version
  * Installation of modules for communication and manipulation with Ansible and PHP
  * Create database Wordpress
  * Create user for Wordpress database and configure it and give privileges for remote access
  * Configure MySQL to accept remote access
