Role Name
=========

Install k8s for tests on Ubuntu 20.04


Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

    k8s_master: bool - для мастер ноды true,  для других false
    master_node_ip:  адрес k8s master

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

