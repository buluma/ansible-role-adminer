# [adminer](#adminer)

Installs Adminer for Database management.

|GitHub|GitLab|Quality|Downloads|Version|Issues|Pull Requests|
|------|------|-------|---------|-------|------|-------------|
|[![github](https://github.com/buluma/ansible-role-adminer/workflows/Ansible%20Molecule/badge.svg)](https://github.com/buluma/ansible-role-adminer/actions)|[![gitlab](https://gitlab.com/buluma/ansible-role-adminer/badges/master/pipeline.svg)](https://gitlab.com/buluma/ansible-role-adminer)|[![quality](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/buluma/adminer)|[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/buluma/adminer)|[![Version](https://img.shields.io/github/release/buluma/ansible-role-adminer.svg)](https://github.com/buluma/ansible-role-adminer/releases/)|[![Issues](https://img.shields.io/github/issues/buluma/ansible-role-adminer.svg)](https://github.com/buluma/ansible-role-adminer/issues/)|[![PullRequests](https://img.shields.io/github/issues-pr-closed-raw/buluma/ansible-role-adminer.svg)](https://github.com/buluma/ansible-role-adminer/pulls/)|

## [Example Playbook](#example-playbook)

This example is taken from `molecule/default/converge.yml` and is tested on each push, pull request and release.
```yaml
---
- name: Converge
  hosts: all
  tasks:
    - name: "Include buluma.adminer"
      include_role:
        name: "buluma.adminer"
```


## [Role Variables](#role-variables)

The default values for the variables are set in `defaults/main.yml`:
```yaml
---
# defaults file for adminer
adminer_download_url: https://www.adminer.org/latest.php
adminer_install_dir: /opt/adminer
adminer_install_filename: adminer.php
adminer_symlink_dirs: []
adminer_add_apache_config: false
```

## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/buluma/ansible-role-adminer/blob/main/requirements.txt).


## [Context](#context)

This role is a part of many compatible roles. Have a look at [the documentation of these roles](https://buluma.github.io/) for further information.

Here is an overview of related roles:

![dependencies](https://raw.githubusercontent.com/buluma/ansible-role-adminer/png/requirements.png "Dependencies")

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://hub.docker.com/u/buluma):

|container|tags|
|---------|----|
|el|all|
|fedora|all|
|opensuse|all|
|ubuntu|all|
|debian|all|

The minimum version of Ansible required is 2.1, tests have been done to:

- The previous version.
- The current version.
- The development version.



If you find issues, please register them in [GitHub](https://github.com/buluma/ansible-role-adminer/issues)

## [Changelog](#changelog)

[Role History](https://github.com/buluma/ansible-role-adminer/blob/master/CHANGELOG.md)

## [License](#license)

Apache-2.0

## [Author Information](#author-information)

[buluma](https://buluma.github.io/)
