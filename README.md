Ansible Role: Win-Import-Cert-mc-fk
=========

Эта роль установит сертификаты УЦ на ОС Windows.

Requirements
------------

None.

Role Variables
--------------

Доступные переменные перечислены вместе со значениями по умолчанию (см. `defaults/main.yml`). Устанавливаются следующие сертификаты:|- сертификаты Головного УЦ Минкомсвязи России в хранилище "Доверенные корневые центры сертификации" (ГОСТ2001-2012);|- сертификаты Удостоверяющего центра Федерального казначейства в хранилище "Промежуточные центры сертификации" (ГОСТ2001-2012);|- сертификат МинФина РФ в хранилище "Доверенные корневые центры сертификации".

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - win_import_cert_mc_fk

License
-------

BSD

Author Information
------------------

Chubik Sergey, sergey.chubik@mail.ru.
Chubik Sergey, chubik@ekaterinburg.fsin.uis.
