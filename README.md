osx-rbenv
=========

An Ansible role to setup rbenv on OS X

Requirements
------------

[Homebrew](http://brew.sh/) must be installed.

Role Variables
--------------

- rbenv_ruby_version: 2.1.2
- rbenv_global_gems:
  - bundler
  - compass

Dependencies
------------

- hnakamur.oh-my-zsh

Example Playbook
----------------

    - hosts: servers
      roles:
         - hnakamur.osx-rbenv

License
-------

MIT

Author Information
------------------

[Hiroaki Nakamura]( http://hnakamur.github.io/ )
