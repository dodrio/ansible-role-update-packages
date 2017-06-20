# update-packages

[![Build Status](https://travis-ci.org/m31271n/ansible-role-update-packages.svg?branch=master)](https://travis-ci.org/m31271n/ansible-role-update-packages)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-m31271n.update-packages-blue.svg)](https://galaxy.ansible.com/m31271n/update-packages)

Ansible role that updates all packages.

## Requirements

None.

## Role Variables

+ `update_packages`: default `true`

## Dependencies

None.

## Example Playbook

```
- hosts: servers
  roles:
    - role: m31271n.update-packages
      update_packages: false
```

* * *

<p align="center">Made with ❤ by <a href="http://index.m31271n.com">m31271n</a></p>
