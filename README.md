Terraform
=========

Installs terraform.

Requirements
------------

None.

Role Variables
--------------

* terraform_version: The version of terraform to install.
* terraform_destination: The location to untar terraform to.
* terraform_unarchive_src: The path to download terraform from.

Dependencies
------------

None.

Example Playbook
----------------

None.

```
- hosts: servers
  roles:
     - { role: terraform }
```

License
-------

MIT

Author Information
------------------

Jordan Murray
https://murrayfoundry.com
