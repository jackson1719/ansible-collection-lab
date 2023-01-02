ansible-linux-motd
=========

[![Build Status](https://travis-ci.org/jackson-t/ansible-linux-motd.svg?branch=master)](https://travis-ci.org/jackson-t/ansible-linux-motd)

This ansible role is based off of yboetz [motd repo](https://github.com/yboetz/motd). 
The scripts have been updated to work with both Ubuntu and CentOS distributions.

During the installation of this role ruby, figlet, and lolcat will be installed to enhance
the output of the MOTD scripts.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: jackson_t.ansible-linux-motd }

License
-------

BSD

Author Information
------------------

This role was created in 2019 by Jackson.
