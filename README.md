ansible-vim
============

This role installs vim

[![Ansible Galaxy](https://img.shields.io/ansible/role/14916.svg)](https://galaxy.ansible.com/salamachinas/vim/)

Requirements
------------

This role requires Ansible 2.0 or higher and platform requirements are listed
in the metadata file.

Install
-------

```sh
ansible-galaxy install salamachinas.vim
```

Tests
-----

```sh
docker build -t test-ansible-vim-centos7 -f tests/Dockerfile_centos7 --force-rm .
docker build -t test-ansible-vim-debian7 -f tests/Dockerfile_debian7 --force-rm .
docker build -t test-ansible-vim-debian8 -f tests/Dockerfile_debian8 --force-rm .
docker build -t test-ansible-vim-ubuntu14 -f tests/Dockerfile_ubuntu14 --force-rm .
docker build -t test-ansible-vim-ubuntu16 -f tests/Dockerfile_ubuntu16 --force-rm .
```
