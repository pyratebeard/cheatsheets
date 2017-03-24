```
____ _ _  _ 
|__| |  \/  
|  | | _/\_ 
```


Print error log

```
errpt
```

Find OS version
```
oslevel -s
```

Change state of services
```
startsrc
stopsrc
lssrc
```

Monitor tools
```
nmon
topas
```

Run smit without being able to make changes
```
smit -x
```

Print configuration
```
prtconf
```

Show lparconfig/stats
```
lparstat -i
```

Paging
```
lsps -a
```

Increase filesystem size
```
chfs -a size=+500M /var
```

Find last password change:
```
lsuser -a lastupdate USERNAME | awk -F= '{print $2}' | xargs perl -le 'print scalar localtime(shift)'
```

Show machine fw
```
lsmcode -a
```
Show Fibre fw
```
lsdev | grep fcs*
lsmcode -d fcs0
```