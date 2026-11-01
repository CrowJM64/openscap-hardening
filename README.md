# Ansible Role for RedHat OpenSCAP Hardening
**Author/Maintainer:** Josh Murphy

## Overview

This Ansible role automates hardening of RedHat distros and derivatives to the CIS Server Level 2 Benchmark using OpenSCAP:

## Tested Platforms and Derivatives
```yaml
Rocky 10,9
Fedora 44,43
Oracle 10,9
AmazonLinux 2027,2023
```

## Example Playbook

```yaml
- hosts: all
  become: yes

  roles:
    - role: openscap_hardening
```

### From Ansible Galaxy

```bash
ansible-galaxy install crowjm64.openscap_hardening
```

This role was created and is maintained by **[CrowJM64](https://github.com/CrowJM64)**.