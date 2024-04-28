# Ansible Installation Guide

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Ansible Version](https://img.shields.io/badge/Ansible-Latest-blue.svg)](https://docs.ansible.com/ansible/latest/index.html)
[![GitHub Issues](https://img.shields.io/github/issues/your/repo.svg)](https://github.com/your/repo/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/your/repo.svg)](https://github.com/your/repo/pulls)

## Overview

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
sudo yum install ansible