Ansible net tools packages Role
================
<p align="right">
  <a href="https://github.com/namiops/ansible_net_tools">
  <img alt="Build" src="https://github.com/namiops/ansible_net_tools/actions/workflows/build.yml/badge.svg">
  <img alt="License" src="https://img.shields.io/github/license/namiops/ansible_net_tools">
  <img alt="Issue" src="https://img.shields.io/github/issues/namiops/ansible_net_tools">
  <img alt="Forfs" src="https://img.shields.io/github/forks/namiops/ansible_net_tools">
  <img alt="Stars" src="https://img.shields.io/github/stars/namiops/ansible_net_tools"> 
  </a>
</p>


Ansible role to install ansible_net_tools packages for networking and mornitoring

Installation
------------
1. Install role with Ansible Galaxy

   ```
   ansible-galaxy install namiops.ansible_net_tools
   ```
2. Then use the role in playbook:

   ```yaml
   - hosts: all
     roles:
       - ansible_net_tools
   ```
3. Run with playbook

   ```shell script
   ansible-playbook playbook.yml -i inventory
   ```

Role Variables
-------------
* net_packages: []

Supporting OS
-------------
* CentOS 8, CentOs 7
* Debian 10, Debian 9
* Ubuntu 20.10, Ubuntu 20.04, Ubuntu 18.04
