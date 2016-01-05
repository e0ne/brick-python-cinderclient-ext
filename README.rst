=============================
python-brick-cinderclient-ext
=============================

OpenStack Cinder Brick client for local volume attachement

Features
--------

* Get volume connector information


Dependencies
------------

Requires dependency::

* python-cinderclient

Optional dependencies based on Cinder driver's protocol::

* open-iscsi, udev - for volume attachment via iSCSI
* ceph-common - for volume attachment via iSCSI (Ceph)
* nfs-common - for volume attachment using NFS protocol

NOTE (e0ne): current version is tested only on Linux hosts

For any other imformation, refer to the parent projects, Cinder and
python-cinderclient::

*  https://github.com/openstack/cinder
*  https://github.com/openstack/python-cinderclient

* License: Apache License, Version 2.0
* Documentation: http://docs.openstack.org/developer/python-brick-cinderclient-ext
* Source: http://git.openstack.org/cgit/openstack/python-brick-cinderclient-ext
* Bugs: http://bugs.launchpad.net/python-cinderclient
