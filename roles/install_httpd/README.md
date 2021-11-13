Install httpd
=========

Install httpd on RedHat

Requirements
------------

The only one thing you need is RedHat

Example Playbook
----------------

Nice to have some conditions

    - hosts: all
      roles:
         - { role: install_httpd, when: ansible_os_family == "RedHat" }
