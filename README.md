Vector
=========

This role install Vector

Requirements
------------

1. ОС Centos versions: 7/8
2. Предустановленное ПО с БД Clickhouse

Role Variables
--------------

Версия Vector описана в файле: [main.yml](defaults%2Fmain.yml)

Список создаваемых директорий и пользователей описан в файле: [main.yml](vars%2Fmain.yml)

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vector }

License
-------

MIT

Author Information
------------------

Evgenyi Korshunov
