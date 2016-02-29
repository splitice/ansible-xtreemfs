mamercad.xtreemfs
=================

Stands up XtreemFS on RHEL/CentOS

Warnings
--------

The role puts SELinux into permissive mode and disables firewalld

Requirements
------------

None

Role Variables
--------------

Set xtreemfs_role in your inventory, as the example below demonstrates

Dependencies
------------

None

Example Playbook
----------------

    - hosts:
        - node1 xtreemfs_role="server"
        - node2 xtreemfs_role="client"
      roles:
        - mamercad.xtreemfs

License
-------

GPLv3

Author Information
------------------

Mark Mercado <mamercad@umflint.edu>
