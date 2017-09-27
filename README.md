# docker-ansible-role

Ansible role to configure lvm volumes.
This role will also create partitions, create vg, lv, and mount logical volumes.

Role Variables
--------------

```
#  
  disknames: "/dev/sdb"
  lvm_partitions: "/dev/sdb1"
  vg_name: "vg_docker"
  lv_name: "lv_docker"
   mount_point: "/var/lib/docker"
```

License
-------

Apache License 2
