riakcs-packages
========

This role will only install Riak CS packages onto a machine.  It could not be bundled with the riakcs role due to the ordering of tasks required while installing a Riak CS cluster.

Requirements
------------

Tested on CentOS 6 and Ubuntu Precise.

Role Variables
--------------

If you have trouble seeing the tables below, please [read the documentation on Github](https://github.com/basho/ansible-riakcs-packages/blob/master/README.md).


| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| riakcs_custom_package       | no            | specify a path on the Ansible control, or HTTP URL, to a custom Riak CS package |
| riakcs_package_release   | 1       | package release|
| riakcs_version| 1.4.4       | Version of Riak CS to install |



Dependencies
------------

Depends on the the basho.riak-common role.

License
-------

Apache

Author Information
------------------

jmartin@baso.com
