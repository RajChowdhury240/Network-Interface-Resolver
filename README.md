# Network-Interface-Resolver
A Simple Tool That Collects Remote Network Interfaces

![Network-Interface-Resolver](https://github.com/Rajchowdhury420/Network-Interface-Resolver/blob/main/project.png)

## Example 

```
Root@Raj:~/Network-Interface-Resolver$  python resolver.py -t 10.10.10.219
[*] Retrieving network interface of 10.10.10.219
Address: Sharp
Address: 10.10.10.219
Address: dead:beef::242e:10cb:f189:9b72
```
This is super useful because it helps you to identify hosts that have additional active interfaces, which usually means, virtual machines, VPNs, connected wireless, docker, etc. Basically "interesting".
