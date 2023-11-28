

```
for i in {2..254} ;do (ping -c 1 10.7.0.$i | grep "bytes from" &) ;don3
```


```
#!/bin/bash
for ip in $(cat ip.txt);do for out in $(sudo nmap -Pn -sS -p- --min-rate 5000 --open $ip | grep open | cut -d '/' -f 1 | tr '\n' ,);do sudo nmap -Pn -sT -p $out -A $ip -oG $ip.txt;done;done
```


```
https://drive.google.com/drive/folders/1EtF9lAPzOqy9KLM074FB0_xonAU0SrCD?usp=drive_link
https://drive.google.com/drive/folders/1EtF9lAPzOqy9KLM074FB0_xonAU0SrCD?usp=sharing
```