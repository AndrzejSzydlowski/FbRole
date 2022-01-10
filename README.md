Filebeat role
=========

Роль для установки filebeat на хостах с ОС: CentOS 7

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------


| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| elasticsearch_version | "7.14.0" | Параметр, который определяет какой версии elasticsearch будет установлен |

Example Playbook
----------------

    - hosts: all
      roles:
         - filebeat

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
