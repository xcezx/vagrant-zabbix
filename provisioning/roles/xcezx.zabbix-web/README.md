zabbix-web [![Build Status](https://travis-ci.org/xcezx/ansible-zabbix-web.svg?branch=master)](https://travis-ci.org/xcezx/ansible-zabbix-web)
========

install and configuration zabbix-web

Requirements
------------

- `httpd`

Role Variables
--------------

Dependencies
------------

- `xcezx.zabbix-repository`

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: xcezx.zabbix-web }

License
-------

BSD
