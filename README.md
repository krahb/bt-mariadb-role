## bt-rhel-role
Ansible bt mariadb role

## description
some basic stuff to setup and keep a simple MariaDB 10.2 updated on Linux
* remember to set your (new) sql root password variable mysql_root_password somewhere in your vault/secrets/groupvars *

## example playbook snippet
```yaml
- import_role:
    name: bt-mariadb-role
  tags:
  - mariadb
```
