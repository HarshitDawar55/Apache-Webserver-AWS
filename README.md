Apache-Webserver-AWS
=========

This role is used to configure Webserver on AWS Cloud Instances based on CentOS like Redhat, CentOS, Amazon Linux, etc.

Requirements
------------

* boto package(because EC2 Module is used).

Role Variables
--------------

Only one variable is used in this role(Web_Doc_Root), no need to explicitly change that, but if you want to change the variable, then you have to update the configuration file of webserver explicitly! 

Dependencies
------------

-

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: tag_Name_Webserver
      roles:
         - Apache-Webserver-AWS

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
