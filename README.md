Bruno Role
==========

This role install Bruno for Linux Debian based and Mac systems.

Requirements
------------

- Linux Debian based system
- MacOS based system
- Ansible

Role Variables
--------------

defaults (current):
- appName: Bruno

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Build ByDefault.

Test
----

``ansible-playbook tests/test.yml -i tests/inventory --syntax-check``

Solo Run

``ansible-playbook tests/test.yml -i tests/inventory``