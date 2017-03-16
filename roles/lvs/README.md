# set vip at boot

```
ansible-playbook -i inventory test.yml -u root -vvvv
```

```
[root@handy2 ~]# ip a
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet 192.168.10.244/32 brd 192.168.10.244 scope global lo:0
       valid_lft forever preferred_lft forever
    inet 192.168.10.220/32 brd 192.168.10.220 scope global lo:1
       valid_lft forever preferred_lft forever
    inet 192.168.10.221/32 brd 192.168.10.221 scope global lo:2
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host
       valid_lft forever preferred_lft forever
```
