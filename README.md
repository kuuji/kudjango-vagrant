# kudjango-vagrant

Vagrant project containing 3 boxes created via packer.

This project allow to deploy :

- One front vagrant box with haproxy
- 2 app vagrant box with kudjango app
- 1 db vagrant box with mysql

Installation and configuration of haproxy / mysql / kudjango app are done using ansible. IP are gathered automatically, nothing to configure for the connection between all vms.

Installation of python and pip on the app vagrant box has been done using a puppet manifest with packer.
