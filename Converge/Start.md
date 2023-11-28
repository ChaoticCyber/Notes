

```
for i in {2..254} ;do (ping -c 1 10.7.0.$i | grep "bytes from" &) ;don3
```