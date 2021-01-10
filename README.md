Apache-Webserver-AWS
=========

This role is used to configure Webserver on AWS Cloud Instances based on CentOS like Redhat, CentOS, Amazon Linux, etc.

Requirements
------------

* boto package(because EC2 Module is used).
* ec2-scripts which will fetch the IP of the EC2 instances dynamically(if dynamic inventory of Ansible is used!).
  * [ec2.py](https://github.com/HarshitDawar55/Ansible/blob/master/Dynamic-Inventory/ec2.py)
  * [ec2.ini](https://github.com/HarshitDawar55/Ansible/blob/master/Dynamic-Inventory/ec2.in)
* If the dynamic Inventory is used, hosts should be assigned using the tags given to the instances!    

Role Variables
--------------

Only one variable is used in this role(Web_Doc_Root), no need to explicitly change that, but if you want to change the variable, then you have to update the configuration file of webserver explicitly! 

Dependencies
------------

Nil

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: tag_Name_Webserver
      roles:
         - Apache-Webserver-AWS

License
-------

[MIT](https://github.com/HarshitDawar55/Apache-Webserver-AWS/blob/master/LICENSE)

Author Information
------------------

[Harshit Dawar](https://www.linkedin.com/in/harshitdawar)
