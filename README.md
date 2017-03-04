Ansible role: PHP-FPM
=========

[![Build Status](https://travis-ci.org/shomatan/ansible-nginx.svg?branch=master)](https://travis-ci.org/shomatan/ansible-php-fpm)

Installs and configures PHP FastCGI Process Manager.

Requirements
------------

None.

Role Variables
--------------

...

Dependencies
------------

+ shomatan.repo-epel
+ shomatan.repo-remi

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
