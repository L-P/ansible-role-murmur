ansible-role-murmur
===================
Install and configure murmur (mumble-server).

Requirements
------------
A Debian-based distribution.

Role Variables
--------------
See the [defaults](defaults/main.yml). Default values come from the default configuration file
installed by murmur on Ubuntu Xenial.

Dependencies
------------
None.

Example Playbook
----------------
```yaml
- hosts: all
  roles:
     - { role: L-P.murmur, become: true }
```

License
-------
MIT
