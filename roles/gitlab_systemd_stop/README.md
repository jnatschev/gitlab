imig.gitlabee.gitlab_systemd_stop
=========

A role to perform `systemctl --user stop gitlab.service`

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Example 1:

    - hosts: fcos01.localdomain
      gather_facts: false
      roles:
         - imig.gitlabee.gitlab_systemd_stop

License
-------

GPL-3.0-or-later

Author Information
------------------

- John Natschev <john.natschev@icloud.com>
