# Ansible Installation Guide  

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Ansible Version](https://img.shields.io/badge/Ansible-Latest-blue.svg)](https://docs.ansible.com/ansible/latest/index.html)

## Overview ---> repo created by sivakumar

This guide provides step-by-step instructions for installing Ansible on your system. Ansible is an open-source automation tool that simplifies IT operations by automating configuration management, application deployment, and task automation.

## Installation Steps

### macOS

1. **Install Homebrew (if not already installed)**:

   Open Terminal and run the following command to install Homebrew:

   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ``` brew install ansible

### Linux
1.Install Ansible:On Debian/Ubuntu systems, run the following command to install Ansible:

### Debian/Ubuntu
```bash 
sudo apt update
sudo apt install ansible
```


### CentOS/RHEL
```bash

sudo yum install epel-release
sudo yum install ansibleWindows
```
 
 ### Verification
To verify that Ansible has been installed correctly, run the following command in your terminal:

```bash
 
ansible --version
```

You should see output displaying the Ansible version and other information.

### Getting Started
Once Ansible is installed,you can start automating tasks and managing your infrastructure efficiently. Refer to the Ansible Documentation for guidance on using Ansible and its various features.

### Feedback and Support
If you encounter any issues during installation or have suggestions for improving this guide, please feel free to submit an issue or contact the Ansible community for assistance.

```
https://www.linkedin.com/in/siva-kumar-kadali-8a459b238/