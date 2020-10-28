andrewrothstein.matchbox-config
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-matchbox-config.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-matchbox-config)

- Installs into a matchbox user+group+home dir
- Schedules matchbox with systemd
- Acquires OS assets for PXE boot
- Supported distributions:
* https://www.flatcar-linux.org/releases/
* https://getfedora.org/en/coreos?stream=stable


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
