ansible-timezone
=========

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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: galexrt.timezone, timezone: UTC }

License
-------

MIT

Author Information
------------------

If you have problems with the role, feel free to create an issue on Github or contact me by mail.
