Ansible role: Wol
=========

[![CI](https://github.com/xiple/ansible-role-wol/actions/workflows/ci.yml/badge.svg)](https://github.com/xiple/ansible-role-wol/actions/workflows/ci.yml)

An ansible role to setup Wake on Lan through ethtool.

Requirements
----------------

None.

Role Variables
----------------

```yaml
wol_ifname: enp1s0
```

The network interface on which to set up Wake-On-Lan paremeter.

Supported distributions
----------------

This role has been been developed and tested on the following distributions :

- Debian : 13

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - xiple.wol
```

License
-------

MIT
