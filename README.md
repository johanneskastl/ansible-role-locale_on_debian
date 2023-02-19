locale_on_debian
=========

Create and set the locale on Debian/Ubuntu systems

Requirements
------------

None.

Role Variables
--------------

- `desired_locale`: The locale you want to have (Default: `de_DE.UTF-8`)

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: 'johanneskastl.locale_on_debian' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
