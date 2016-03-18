# ansible-nginx-uwsgi-supervisor-flask

Add flask to this code
https://github.com/dorianpula/ansible-nginx-uwsgi-supervisor

An Ansible role to setup and manage a Flask UWSGI app via supervisor, and served up on a NGINX web server.  The goal of this
role is to make deployment of WSGI app as a simple and sane as possible.  Additionally the role provides sane defaults
for logging and folder structure setup.

Requirements
------------

- aptitude or python-apt (required by apt tasks)
- python > 2.5 (required by ini_file tasks)

Distros tested
------------

This role is designed to work against a modern Ubuntu system.  (Tested on Ubuntu 13.10 and 14.04)  It should 
theoretically work on older versions of Ubuntu or Debian based systems.

```
ansible-playbook -i hosts flask.yml
```
