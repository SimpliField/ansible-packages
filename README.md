Install ubuntu/debian packages
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
