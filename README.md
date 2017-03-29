Setup Drush
=========

Performs misc drush setup tasks for multiple installations on a host.

* Runs `drush init` on remote machine.
* Customizes `~/.drush/drushrc.php` on remote machine.
* Creates aliases on host and remote machines.

Requirements
------------

Drush installed on remote machine.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: kentr.setup-drush, installations: list_of_installations }

License
-------

BSD 3-Clause

Author Information
------------------

Kent Richards, https://kentrichards.net
