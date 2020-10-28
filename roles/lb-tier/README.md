Role Name
=========

This role will install haproxy and apply the required configuration

Requirements
------------

N/A

Role Variables
--------------

  - payload: name of the haproxy package and service
  - load_balancer_packages: Packages to install for haproxy

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - lb-tier

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
