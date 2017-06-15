andrewrothstein.luigi
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-luigi.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-luigi)

Installs [luigi](https://github.com/spotify/luigi).

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
    - andrewrothstein.luigi
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
