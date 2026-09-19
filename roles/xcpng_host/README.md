xcpng_host role
===============

This Ansible role configures a freshly installed or upgraded XCP-ng machine
with SRCF customisations.

It is closely based on, and replaces, the `xcpngtweak` (formerly
`xenservertweak`) bash script that was used in the past.

Requirements
------------

XCP-ng must already be installed on the host to be configured with this role.

Role Variables
--------------

TODO

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

TODO

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

TODO

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT License.  See LICENSE at the top of the repository.
