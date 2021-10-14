vsftpd
======

Installs vsftpd package and some basic config.

Requirements
------------

None.

Role Variables
--------------

vsftpd_anon_enable - enables anonymous read access to /var/ftp/pub
vsftpd_anon_upload - additionally enables anonymous write access to /var/ftp/pub/upload

Dependencies
------------

None.

Example Playbook
----------------

- hosts: ftpservers
  roles:
    - vsftpd

License
-------

BSD

Author Information
------------------

Mikhail Kalmykov
