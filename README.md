ROLE_NAME
=========

[![Build Status](https://travis-ci.org/jebovic/ansible-ROLE_NAME.svg?branch=master)](https://travis-ci.org/jebovic/ansible-ROLE_NAME) [![Ansible Galaxy](https://img.shields.io/badge/galaxy-jebovic.ROLE_NAME-blue.svg?style=flat)](https://galaxy.ansible.com/jebovic/ROLE_NAME)

Install and configure ROLE_NAME

Role Variables
--------------

```
```

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: jebovic.ROLE_NAME }
```

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
