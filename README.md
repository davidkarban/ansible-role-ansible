Ansible
=========

Role install ansible trhu ansible (on remote servers).

Requirements
------------

Epel repository on RHEL and clones. None on Debian/Ubuntu.


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: davidkarban.ansible }

License
-------

Apache 2.0
