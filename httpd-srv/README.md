httpd-srv
=========

Installs httpd package with the simple start page.

Requirements
------------

None.

Role Variables
--------------

admin_email variable is used.

The following target host facts are used as well:
- ansible_fqdn
- ansible_system
- ansible_distribution

Dependencies
------------

None.

Example Playbook
----------------

- hosts: webservers
  roles:
    - httpd-srv

License
-------

BSD

Author Information
------------------

Mikhail Kalmykov
