# zabbix-map-creation
Динамическое создание карт топологии сетевого оборудования в Zabbix с помощью lldp и API. Скрипт использует библиотеку https://napalm.readthedocs.io/en/latest/, работает только на Arista EOS.

`./lldp2dot2zabbix.py -u dot -p dot -s zabbix.example.com -g ghArista -m Arista_map`
