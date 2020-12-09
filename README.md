# Network-Interface-Resolver
A Simple Tool That Collects Remote Network Interfaces


## Example 

```
Root@Raj:~/Network-Interface-Resolver$ python resolver.py -t 10.10.11.3
[*] Retrieving network interface of 10.10.11.3
Address: HYPERV1
Address: 192.168.57.1
Address: 192.168.2.1
Address: 192.168.77.201
Address: 10.10.11.3
```
This is super useful because it helps you to identify hosts that have additional active interfaces, which usually means, virtual machines, VPNs, connected wireless, docker, etc. Basically "interesting".
