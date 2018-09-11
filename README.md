rd-ansible-hosts [![Build Status](https://travis-ci.org/bbc/rd-ansible-hosts.svg?branch=master)](https://travis-ci.org/bbc/rd-ansible-hosts)
=========

This role configures the hostname of a machine and the hosts file. By default it simply points towards itself and allows for custom hosts to be added.

Requirements
------------

This role requires Ansible 2.6

Role Variables
--------------

See defaults for variables and descriptions

Example Playbook
----------------

Example to call:

    - hosts: all
      roles:
         - { role: rd-ansible-hosts }
