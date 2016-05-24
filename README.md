Install ubuntu/debian packages [![Build Status](https://travis-ci.org/SimpliField/ansible-packages.svg?branch=master)](https://travis-ci.org/SimpliField/ansible-packages) [![Ansible Role](https://img.shields.io/ansible/role/9904.svg?maxAge=2592000)](https://galaxy.ansible.com/SimpliField/packages/)
=========

Setup ubuntu/debian package(s)

Requirements
------------

Need ansible 2+

Role Variables
--------------



Dependencies
------------

There is no dependency.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
   - { role: SimpliField.packages, packages: [git] }
   - { role: SimpliField.packages, packages: [{name: pymongo, state: present, update: true}] }
```

License
-------

BSD
