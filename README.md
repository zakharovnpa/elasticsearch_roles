Elasitcsearch role
=========

Роль для установки Elasitcsearch на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| elasitcsearch_version | "7.14.0" | Параметр, который определяет какой версии Elasitcsearch будет установлен |

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: elasticsearch_roles }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
- Zakharov Sergey, Netology student of DevOps engeneers course.
- This version 0.0.01 file README.md

