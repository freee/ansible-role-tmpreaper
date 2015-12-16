tmpreaper
=========

Install and configure tmpreaper.

Requirements
------------

none

Role Variables
--------------

Available variables are listed below, along with default values:

```yaml
tmpreaper_time: '7d'
tmpreaper_protect_extra: ''
tmpreaper_dirs: '/tmp/.'
tmpreaper_delay: '256'
tmpreaper_additionaloptions: ''
```

Dependencies
------------

none

Example Playbook
----------------

```yaml
- hosts: web-server
  roles:
    - role: freee.tmpreaper
      tmpreaper_time: '1d'
```

License
-------

Apache License 2.0
