Role Name
=========

This role will install postgres, aply baseline config, initialice the DB, create postgres db and user. 

Requirements
------------

N/A

Role Variables
--------------

  - postgres_rhel7_repo: Postgres repository to download the required packages
  - postgres_packages: Postgres and its components that need to be installed
  - postgres_library: required python library
  - postgres_10_data_dir: Location of postgres db
  - postgres_10_bin_path: Location of postgres binary
  - postgres_service: Postgres servive name
  - postgres_port: Postgres port
  - postgres_user: User that will run postgres
  - postgres_users: database users 
  - postgres_databases: database to be created

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - db-tier

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
