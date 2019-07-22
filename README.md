Update
=========

This Ansible Role is used to update all your remote machines that are Linux based. It first uses your package manager to force an update to your remote machines and registers facts based on that tasks to determine whether to reboot or not based on whether the machine update.
Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------
no variables were used in making this role

Dependencies
------------

no other roles were used in making this role

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - update

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
