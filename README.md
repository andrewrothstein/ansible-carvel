andrewrothstein.carvel
=========

![Build Status](https://github.com/andrewrothstein/ansible-carvel/actions/workflows/build.yml/badge.svg)

Installs [carvel](https://carvel.dev/) tools like ytt, kapp, et. al.

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
    - andrewrothstein.carvel
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
