# Ansible Capstone: Deploying WordPress with MySQL

This project was completed as part of the Connecting to Web-Based Systems Capstone Project.
It showcases my ability to use Ansible for configuration management and automation by deploying a full WordPress site connected to a MySQL database on a local server.

## Project Overview
* Automates the installation and configuration of WordPress.

* Sets up and configures a MySQL database using the geerlingguy.mysql role.

* Installs and configures Apache and PHP packages for WordPress.

* Uses Ansible roles, handlers, and templates to manage services and configuration files.

* Final deployment results in a fully functional local WordPress site.

## Tech Stack
* Ansible

* WordPress

* MySQL

* Apache

* PHP

## Quick Start
### Clone the repo
```git clone git@github.com:mahmoudnasser1561/Ansible-Capstone.git
cd Ansible-Capstone
```

### Install Dependencies
```
ansible-galaxy install -r requirements.yml
```

### Run the Playbook
```
ansible-playbook wordpress.yml
```
