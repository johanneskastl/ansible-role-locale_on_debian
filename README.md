![Ansible Lint](https://github.com/johanneskastl/ansible-role-locale_on_debian/workflows/Ansible%20Lint/badge.svg)

locale_on_debian
=========

Create and set the locale on Debian/Ubuntu systems.

Requirements
------------

None.

Role Variables
--------------

- `desired_locale`: The locale you want to have (Default: `de_DE.UTF-8`)
- `default_locale`: The default locale (Default: `None`)

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: 'johanneskastl.locale_on_debian'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via git@johannes-kastl.de.
