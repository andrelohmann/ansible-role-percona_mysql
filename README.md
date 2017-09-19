percona_mysql
=============

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-percona_mysql.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-percona_mysql)

Use this role to install percona-server-5.7 on your debian or ubuntu server.

Requirements
------------

This role requires debian or ubuntu.

Role Variables
--------------

The default set of variables defines the percona installation and needs at best to be overwritten in group_vars/host_vars

    percona_mysql_version: '5.7'

The following mandatory variables need to be set in group_vars/host_vars

    percona_mysql_root_password: SOMELONGPASSWORD



Example Playbook
----------------

    - hosts: percona
      roles:
         - { role: andrelohmann.ansible-role-percona_mysql }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
