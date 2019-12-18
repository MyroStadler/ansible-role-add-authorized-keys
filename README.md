Add Authorized Keys
===================

Add lines to the remote user's `~/.ssh/authorized_keys` file.

Requirements
------------

None

Role Variables
--------------

add_authorized_keys[]

Dependencies
------------

None

Example Playbook
----------------

```
- hosts: servers
  roles:
     - { role: myrostadler.add_authorized_keys }
```

License
-------

GPL-3.0-only

Author Information
------------------

Myro Stadler
