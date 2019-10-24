Role Name
=========

The cow say motd

Requirements
------------

Need to be able to install EPEL rpm over internet

Role Variables
--------------

cowsay_motd_message: The message to be displayed

Dependencies
------------

Perl

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: cowsay_motd
           cowsay_motd_message: "Get off my server"

License
-------

BSD

Author Information
------------------

Eric Chong
