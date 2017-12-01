Configure Katello
=========

This Role configures and manages Katello, well that is its aim. Right now it works for Red Hat Satellite 6.2, which is my current usecase.
It would be trvial to get it working with a new version or Katello, PRs welcome.

Requirements
------------

Requires Ansible Modules in https://github.com/theforeman/foreman-ansible-modules

Role Variables
--------------

See defaults/mail.yml file 

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: sean797.configure_katello }
