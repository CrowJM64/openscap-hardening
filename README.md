# Ansible Role for RedHat OpenSCAP Hardening
**Author/Maintainer:** Josh Murphy

## Overview

This Ansible role automates hardening of Linux operating systems to the CIS Server Level 2 Benchmark using OpenSCAP.

## Explicitly Tested Platforms
```yaml
# RedHat
Rocky 10,9
Fedora 44,43
Oracle 10,9
AmazonLinux 2027,2023

# Debian
Ubuntu 24.04
Debian 13,12
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