zabbix-repo Role
=========

Install the zabbix repository.

[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-neoloc.zabbix-repo-blue.svg)](https://galaxy.ansible.com/neoloc/ansible-role-zabbix-repo/)


Requirements
------------

None


Role Variables
--------------
```yaml
zabbix_repository_configure: true
zabbix_repository_version_major: "6.2"
zabbix_repository_version_minor: 1
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
         - neoloc.zabbix-repo

License
-------

See license.md

Author Information
------------------

[![Github](https://img.shields.io/badge/Github-neoloc-blue.svg)](https://github.com/neoloc)
