Ansible Role HyperHDR
=========

[![CI](https://github.com/aleksanderbl29/ansible-role-hyperhdr/actions/workflows/ci.yml/badge.svg)](https://github.com/aleksanderbl29/ansible-role-hyperhdr/actions/workflows/ci.yml) ![Galaxy downloads](https://img.shields.io/ansible/role/d/aleksanderbl29/hyperhdr)


A role to deploy HyperHDR on debian based systems.

Is tested on Ubuntu 2204 and 2404 and Debian 11 and 12 through molecule. I use it in my environment with RpiOS based on Debian 11.

Requirements
------------

None

Role Variables
--------------

Verification checks (post-install) can be disabled with the following variables. I recommend against this, but it may be useful.

```
disable_verification: false
disable_conn_validation: false
disable_service_validation: false
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
        - aleksanderbl29.hyperhdr

License
-------

GPL v3

Author Information
------------------

This role was created in 2024 by [Aleksander Bang-Larsen](https://github.com/aleksanderbl29)
