imig.gitlabee.gitlab_change_image_in_systemd_user_unit_file
=========

This role is to change the gitlab systemd user unit file `Image` value on a gitlab-ee image version change.

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

    - name: Run `imig.gitlabee.gitlab_change_image_in_serviced_user_unit_file` role
      gather_facts: false
      hosts: fcos01.localdomain
      roles:
         - imig.gitlabee.gitlab_change_version_in_systemd_user_unit_file

License
-------

GPL-3.0-or-later

Author Information
------------------

- John Natschev <john.natschev@icloud.com>
