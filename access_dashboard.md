# https://<ip-address>:<nodePort-of-ingress-controller>

----example---------------
NAME                                         TYPE        CLUSTER-IP       EXTERNAL-IP   PORT(S)                      AGE
service/ingress-nginx-controller             NodePort    10.106.162.153   <none>        80:31976/TCP,443:30478/TCP   72m
$ ip a

3: enp0s8: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:55:76:66:08 brd ff:ff:ff:ff:ff:ff
    inet 192.168.200.11/24 brd 192.168.200.255 scope global enp0s8
       valid_lft forever preferred_lft forever
    inet6 fe80::a00:yyff:fe76:b008/64 scope link 
    
    https://192.168.200.11:30478
