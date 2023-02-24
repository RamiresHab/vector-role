Vector-role
=========

Эта роль разворачивает сервер vector для обработки логов, поступающих в Clickhouse.

Requirements
------------
Для работы этой роли требуется ansible версии 2.10 или выше.

Role Variables
--------------

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `vector_version` | 0.27.0 | Версия vector |
| `vector_package` | vector | название пакета для установкиvector |

Dependencies
------------

Для работы этой роли необходимо предварительно поднять сервер с Clickhouse. Эту роль можно применить на сервер с ОС Ubutu 22.04 и выше.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - vector-role 

License
-------

MIT

Author Information
------------------

Roman Khabibullin
