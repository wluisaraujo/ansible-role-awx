[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-AWX-blue.svg)](https://galaxy.ansible.com/wluisaraujo/iac-ansible-awx)  [![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-awx.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-awx)
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [AWX](https://github.com/ansible/awx)
------------

Description
------------

 * Ansible for AWX

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.awx
```

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-awx
...    
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
