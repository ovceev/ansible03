Install vsftpd
=========

Install vsftpd on RedHat

Requirements
------------

The only one thing you need is RedHat

Example Playbook
----------------

Nice to have some conditions

    - hosts: all
      roles:
         - { role: install_vsftpd, when: ansible_os_family == "RedHat" }
