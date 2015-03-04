devstack-cinder-backup
======================
Devstack with Cinder-Backup

Prerequisites:
--------------
- DevStack setup requires to have 1 VM/ BM machine with internet connectivity.
- Setup a fresh supported Linux installation. (Ubuntu/Fedora/CentOs)
- Install Git

Steps
-----
Clone devstack
```
$git clone https://github.com/openstack-dev/devstack.git
```

Clone devstack-cinder-backup
```
$git clone https://github.com/svashu/devstack-cinder-backup.git
```

Copy localrc from devstack-cinder-backup to devstack
```
$ cp devstack-cinder-backup/localrc devstack

```

Modify the devstack/localrc for IP and password modifications

Deploy your Devstack

```
$cd devstack && ./stack.sh
```
