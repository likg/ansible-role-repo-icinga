[![Build Status](https://travis-ci.org/likg/ansible-role-repo-icinga.svg?branch=master)](https://travis-ci.org/likg/ansible-role-repo-icinga)

# Ansible Role: Icinga2 repo

Install Icinga2 repo.

## Requirements

No special requirements.

## Role Variables

Available variables/default values can be found in [defaults/main.yml](defaults/main.yml).

## Dependencies

None for Debian/Ubuntu. TODO: depend on yum-repo-epel role for RedHat

```yaml
dependencies:
  - { role: likg.yum-repo-epel, when: ansible_os_family == 'RedHat' }
```

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
