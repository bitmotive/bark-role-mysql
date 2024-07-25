BARK: MYSQL
=========

Install MYSQL with sane defaults.

Requirements
------------

All roles in the Bitmotive Ansible Role Kit are configuration driven.

Customize this role by providing environment variables in either your
shell environment, host specific in group_vars/, or at the CLI when
prompted at runtime. 

Role Variables
--------------

**MYSQL_ROOT_PASSWORD**:

The root password for the MySQL installation.


Dependencies
------------

Currently dependent on Debian/Ubuntu due to reliance on `apt` and filepath 
assumptions. 

License
-------

MIT

Author Information
------------------

A Bitmotive Project: Build. Incubate. Train.
https://bitmotive.com 
