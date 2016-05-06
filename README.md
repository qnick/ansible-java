Installing specified version of oracle java 
===============================

Requirements:
------------

Ansible ver. 2.0 or later

Example:
-------
Installing both 7 and 8 java versions (the last one - 7 - will became default)

```
---
- hosts: test
  gather_facts: no
  roles:
    - { role: java, version: 8 }
    - { role: java, version: 7 }

```
