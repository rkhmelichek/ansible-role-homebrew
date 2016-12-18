Homebrew
========

[![Build Status](https://travis-ci.org/rkhmelichek/ansible-role-homebrew.svg?branch=master)](https://travis-ci.org/rkhmelichek/ansible-role-homebrew)

Installs [Homebrew](http://brew.sh/) on macOS.

Requirements
------------

None.

Role Variables
--------------

    homebrew_prefix: the Homebrew installation parent directory

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: localhost
      roles:
        - rkhmelichek.homebrew

License
-------

BSD

Author Information
------------------

[Roman Khmelichek](http://romankh.me/)
