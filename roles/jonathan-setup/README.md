Role Name
=========

Adds a user 'jonathan' by default, checks out and configures oh-my-zsh and add my dotfiles. 
Installs basic cli tools. 


Requirements
------------

Debian only a the moment.

Role Variables
--------------

default_user: jonathan
default_user_password: abc123

Dependencies
------------

None

Example Playbook
----------------

---

- hosts: all
  remote_user: pi
  become: yes
  roles:
    - role: jonathan-setup

License
-------

BSD

Author Information
------------------

Jonathan Hart - http://heyup.me - https://github.com/jphart/
