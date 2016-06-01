Role Name
=========

This roles provisions a Spring Boot application.

Requirements
------------

No pre-requisites needed.


Role Variables
--------------

## spring_boot_application_id
Sets the application id which is uses thorugh the role to derive usernames, folders where the application will be installed, and so on. Defaults to `springbootapplication`

## spring_boot_http_port
Sets the HTTP port for the Spring Boot application, defaults to `8080`


Dependencies
------------

No dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    hosts: localhost
    roles:
    - { role: ansible-springboot-role, 
        spring_boot_file_source_local: 'example-application.jar' 
      }

License
-------

BSD

Author Information
------------------

Christian Pelster, pelle@pelle.io, https://github.com/pellepelster/ansible-springboot-role
