andrewrothstein.{{ cookiecutter.galaxy_name }}
===========================
![Build Status]({{ cookiecutter.github_root }}/{{ cookiecutter.github_org }}/{{ cookiecutter.github_project }}/actions/workflows/build.yml/badge.svg)

{{ cookiecutter.role_desc_md }}

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
    - {{ cookiecutter.galaxy_org }}.{{ cookiecutter.galaxy_name }}
```

License
-------

MIT

Author Information
------------------

{{ cookiecutter.mit_license_holder }} <{{ cookiecutter.mit_license_email }}>
