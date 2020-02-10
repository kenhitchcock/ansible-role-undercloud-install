Role Name
=========

> Red Hat Openstack undercloud installation.

Configures all the requirements for the undercloud installation.

Requirements
------------

Prebuilt system with at least two network cards attached.

Valid subscription to OpenStack. All repositories need to be enabled.
Recommend using my role for registering your systems to cdn or satellite.
ansible-role-redhat-register


Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

    # No are required to be overwirtten for now. defaults/main.yaml has variables set for basic installation. 


Future Releases
---------------

 - Add support for detailed undercloud.conf configuration.

License
-------

MIT

Author Information
------------------

Ken Hitchcock [Github](https://github.com/kenhitchcock)

