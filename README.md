# dumplsarpc
RID Cycling Tool | Simple rpcclient wrapper | AD Enumeration

This enumeration technique should work if we have access **/pipe/lsarpc**.  

We should try this out if we ever have read access on the **IPC$** share.  

netexec has this function already. This little project is just a noobs exercise.

```sh
nxc smv -u 'guest' -p '' --rid-brute 1500 dc01
```

![](example.png)

happy hacking
