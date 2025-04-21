ansible-role-opentofu
=========

Sets up the APT repository and installs the OpenTofu package according to <https://opentofu.org/docs/intro/install/deb/>.

Requirements
------------

No special requirements.

Role Variables
--------------

No variables.

Dependencies
------------

No dependencies.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: gehock.ansible_role_opentofu }
```

License
-------

MIT

Author Information
------------------

Sami Laine, <https://github.com/Gehock>
