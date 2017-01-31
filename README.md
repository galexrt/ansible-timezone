ansible-timezone
=========

[![Build Status](https://travis-ci.org/galexrt/ansible-.svg?branch=master)](https://travis-ci.org/galexrt/ansible-)

Ansible role for setting/changing the timezone.

Requirements
------------

No special requirements.
The systems must be using `timedatectl` or `/etc/localtime` to configure time.

Role Variables
--------------

* `timezone` - Set it to the wanted timezone.
* `timezone_use_local_rtc` - When timedatectl is used, allows to set rtc.`

Dependencies
------------

No dependencies.

Example Playbook
----------------

An example playbook on how to use this role:

```
- hosts: servers
  roles:
     - { role: galexrt.timezone, timezone: "UTC" }
```

License
-------

MIT

Author Information
------------------

If you have problems with the role, feel free to create an issue on Github or contact me by mail.
