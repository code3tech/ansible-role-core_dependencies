# [core_dependencies](#core_dependencies)

Install dependecies to support the Ansible core modules.

|GitHub|GitLab|Quality|Downloads|Version|
|------|------|-------|---------|-------|
|[![github](https://github.com/robertdebock/ansible-role-core_dependencies/workflows/Ansible%20Molecule/badge.svg)](https://github.com/robertdebock/ansible-role-core_dependencies/actions)|[![gitlab](https://gitlab.com/robertdebock/ansible-role-core_dependencies/badges/master/pipeline.svg)](https://gitlab.com/robertdebock/ansible-role-core_dependencies)|[![quality](https://img.shields.io/ansible/quality/43778)](https://galaxy.ansible.com/robertdebock/core_dependencies)|[![downloads](https://img.shields.io/ansible/role/d/43778)](https://galaxy.ansible.com/robertdebock/core_dependencies)|[![Version](https://img.shields.io/github/release/robertdebock/ansible-role-core_dependencies.svg)](https://github.com/robertdebock/ansible-role-core_dependencies/releases/)|

## [Example Playbook](#example-playbook)

This example is taken from `molecule/default/converge.yml` and is tested on each push, pull request and release.
```yaml
---
- name: converge
  hosts: all
  become: yes
  gather_facts: yes

  roles:
    - role: robertdebock.core_dependencies
```

The machine needs to be prepared. In CI this is done using `molecule/default/prepare.yml`:
```yaml
---
- name: prepare
  hosts: all
  become: yes
  gather_facts: no

  roles:
    - role: robertdebock.bootstrap
```

Also see a [full explanation and example](https://robertdebock.nl/how-to-use-these-roles.html) on how to use these roles.


## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/robertdebock/ansible-role-core_dependencies/blob/master/requirements.txt).

## [Status of used roles](#status-of-requirements)

The following roles are used to prepare a system. You can prepare your system in another way.

| Requirement | GitHub | GitLab |
|-------------|--------|--------|
|[robertdebock.bootstrap](https://galaxy.ansible.com/robertdebock/bootstrap)|[![Build Status GitHub](https://github.com/robertdebock/ansible-role-bootstrap/workflows/Ansible%20Molecule/badge.svg)](https://github.com/robertdebock/ansible-role-bootstrap/actions)|[![Build Status GitLab ](https://gitlab.com/robertdebock/ansible-role-bootstrap/badges/master/pipeline.svg)](https://gitlab.com/robertdebock/ansible-role-bootstrap)|

## [Context](#context)

This role is a part of many compatible roles. Have a look at [the documentation of these roles](https://robertdebock.nl/) for further information.

Here is an overview of related roles:
![dependencies](https://raw.githubusercontent.com/robertdebock/ansible-role-core_dependencies/png/requirements.png "Dependencies")

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://hub.docker.com/u/robertdebock):

|container|tags|
|---------|----|
|alpine|all|
|amazon|Candidate|
|el|all|
|debian|all|
|fedora|all|
|opensuse|all|
|ubuntu|all|

The minimum version of Ansible required is 2.10, tests have been done to:

- The previous version.
- The current version.
- The development version.


If you find issues, please register them in [GitHub](https://github.com/robertdebock/ansible-role-core_dependencies/issues)

## [License](#license)

Apache-2.0

## [Author Information](#author-information)

[robertdebock](https://robertdebock.nl/)

Please consider [sponsoring me](https://github.com/sponsors/robertdebock).
