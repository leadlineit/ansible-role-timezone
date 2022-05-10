# Ansible Galaxy Role Timezone

![Build Status](https://github.com/leadlineit/ansible-role-timezone/actions/workflows/ansible-galaxy-ci.yml/badge.svg)
[![Galaxy Role](https://img.shields.io/badge/Ansible--Galaxy-leadlineit.timezone-blue.svg?logo=ansible&logoColor=white)](https://galaxy.ansible.com/leadlineit/timezone/)

This role helps to manage timezone on a Debian (stretch/buster/bullseye).

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

The variable that can be passed to this role and a brief description about them are as follows:

```yaml
---
timezone: America/New_York
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
    - { role: leadlineit.timezone, tags: timezone }
```

License
-------

MIT

Author Information
------------------

This role was created by Stas Stavnichuk.
