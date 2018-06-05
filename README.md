[![Ansible Galaxy](https://img.shields.io/badge/role-likg.repo--icinga-blue.svg?style=flat)](https://galaxy.ansible.com/likg/repo-icinga/)
[![Build Status](https://travis-ci.org/likg/ansible-role-repo-icinga.svg?branch=master)](https://travis-ci.org/likg/ansible-role-repo-icinga)

# Ansible Role: Icinga2 repo

Install Icinga2 repo.

## Requirements

No special requirements.

## Role Variables

Available variables/default values can be found in [defaults/main.yml](defaults/main.yml).

## Dependencies

None for Debian/Ubuntu, `likg.yum-repo-epel` for RedHat.

## Example Playbook

```yaml
    - hosts: servers
      become: yes
      roles:
        - { role: likg.repo-icinga }
```

## License

MIT

## Author Information

This role was created by Lik.
