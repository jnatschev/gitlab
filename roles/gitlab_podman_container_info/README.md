imig.gitlabee.gitlabee_podman_container_info
=========

Ansible collection, imig.gitlabee, role to get gitlab-ee podman container information.

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

    - gather_facts: false
      hosts: fcos-node01.ctmps.com.au
      name: Run role ctmps.gitlab.gitlabps_get_current_image play
      roles:
         - imig.gitlabee.gitlabee_podman_container_info

License
-------

GPL-3.0-or-later

Author Information
------------------

- John Natshev <john.natschev@icloud.com>
