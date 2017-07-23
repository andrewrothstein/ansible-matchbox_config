andrewrothstein.matchbox-config
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-matchbox-config.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-matchbox-config)

Installs matchbox user, group, and registers with process supervisor. Currently supports systemd.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.matchbox-config
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
