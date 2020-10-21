apt_config
=========

Minimal APT configuration and unattended upgrades.

Role Variables
--------------
* apt_packages
```
# default
apt_packages:
  - aptitude
  - ufw
  - ...
```
* apt_admin_email
```
# Either specify it in vars/ or look at the example.
apt_admin_email: some@email
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: frite.apt_config, apt_admin_email: "some@email" }

License
-------

MIT
