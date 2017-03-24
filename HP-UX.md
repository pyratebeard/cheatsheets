```
_  _ ___     _  _ _  _ 
|__| |__] __ |  |  \/  
|  | |       |__| _/\_ 
```

Start and stop `ssh` service
```
/sbin/init.d/secsh {start|stop|start_msg|stop_msg}
```

Kernel bit check
```
getconf KERNEL_BITS
```

Show swap info
```
swapinfo
```
    
Display network packets
```
nettl -start
nettl -status all
```

Display disk usage
```
bdf
```

Display disk usage
```
df -v
```

Show hardware details
```
/opt/ignite/bin/print_manifest
```

Show server information including installed packages
```
print_manifest
```

Show server information
```
cat /var/opt/ignite/local/manifest/manifest.info
```

Show hardware architecture (rX = Itanium, rP = PA-RISC)
```
model
```
