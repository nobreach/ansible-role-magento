Role Name
=========

Install magento2 2.1.7 and setup sample data

Role Variables
--------------

Magento `setup:install` variables should be set accordingly

- admin_firstname
- admin_lastname
- admin_email
- admin_user
- admin_password

Dependencies
------------

- nobreach.php
- nobreach.mysql

To get PHP 7 and MySQL 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: php
      vars:
        - admin_firstname: Yakov
        - admin_lastname: ...
        - admin_email: ...
        ...
      roles:
        - { role: nobreach.magento }

License
-------

BSD

