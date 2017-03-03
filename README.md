Ansible role: PHP-FPM
=========

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
