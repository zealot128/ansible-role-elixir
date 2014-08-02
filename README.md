Elixir + Erlang
========

Installs latest Elixir + Erlang on Ubuntus.

Erlang: vi apt-repository

Elixir: Download of precompiled release from Github, unzipping to /usr/local/src/elixir-VERSION and symlinking the necessary binaries into /usr/local/src

Requirements
------------

Ubuntu

Role Variables
--------------

There is only 1 variable now:

```yaml
elixir_version: 0.14.2
```


Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
      - { role: zealot128.elixir elixir_version: '0.14.2' }
```

License
-------

BSD

