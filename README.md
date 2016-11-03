ROLE_NAME
=========

[![Build Status](https://travis-ci.org/jebovic/ansible-ROLE_NAME.svg?branch=master)](https://travis-ci.org/jebovic/ansible-ROLE_NAME) [![Ansible Galaxy](https://img.shields.io/badge/galaxy-jebovic.ROLE_NAME-blue.svg?style=flat)](https://galaxy.ansible.com/jebovic/ROLE_NAME)

Install and configure ROLE_NAME

This role is a part of my [OPS project](https://github.com/jebovic/ops), follow this link to see it in action. OPS provides a lot of stuff, like a vagrant file for development VMs, playbooks for roles orchestration, inventory files, examples for roles configuration, ansible configuration file, and many more.

Role Variables
--------------

```yaml
```

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: jebovic.ROLE_NAME }
```

Tags
----

* ROLE_NAME_config : only update config and restart service

Add slack notifications
-----------------------

```
travis encrypt "jebovic:TRAVIS_TOKEN" --add notifications.slack
```

License
-------

MIT

Author Information
------------------

Jérémy Baumgarth https://github.com/jebovic
