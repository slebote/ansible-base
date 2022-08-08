# ansible-base

Ansible base project

## Included

* Ansible local configuration file : `ansible.cfg`
* Ansible local inventory file : `hosts`
* Playbook based on Roles
* Common Role with some example
* Grouped variables firectory with `all.yml` file

## How to it works

1. Configure Ansible into `ansible.cfg` if necessary
2. Configure you inventory into `hosts` file
3. Configure you variables within `group_vars` directory
4. Define Roles based on `roles/common` into `roles` directory
5. Configure you playbook(s) based on `playbook.yml`

## How to launch

Simple call :

```
ansible-playbook playbook.yml
```

List playbook tasks :

```
ansible-playbook playbook.yml --list-tasks
```
