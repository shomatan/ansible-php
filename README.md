Ansible role: PHP-FPM
=========

[![Build Status](https://travis-ci.org/shomatan/ansible-nginx.svg?branch=master)](https://travis-ci.org/shomatan/ansible-php-fpm)

Installs and configures PHP FastCGI Process Manager.

Requirements
------------

None.

Role Variables
--------------
See `defaults/main.yml`

Dependencies
------------

+ shomatan.repo-epel
+ shomatan.repo-remi

Role Tags
---------

- php-fpm-install
- php-fpm-config
- php-fpm-service

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: shomatan.php-fpm }

License
-------

BSD, MIT

Author Information
------------------
