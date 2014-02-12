riakcs-packages
========

This role will only install Riak CS packages onto a machine.  It could not be bundled with the riakcs role due to the ordering of tasks required while installing a Riak CS cluster.

Requirements
------------

None

Role Variables
--------------




| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| riakcs_custom_package       | no            | path to a custom Riak CS package |
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
