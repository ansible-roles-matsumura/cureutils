[![](https://github.com/ansible-roles-matsumura/cureutils/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/cureutils/actions?query=workflow%3Abuild)

Role Description
=========

Installs [Cureutils](https://github.com/greymd/cureutils) for CentOS7.

Requirements
------------

EPEL and Ruby installed before running this role.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - geerlingguy.repo-epel
    - geerlingguy.ruby
    - cureutils
```

License
-------

BSD
