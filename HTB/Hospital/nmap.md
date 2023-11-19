```
┌──(root㉿kali)-[/home/kali]
└─# nmap -Pn -sS -p- 10.10.11.241 --open --min-rate 5000
Starting Nmap 7.94SVN ( https://nmap.org ) at 2023-11-19 12:17 EST
Nmap scan report for 10.10.11.241
Host is up (0.34s latency).
Not shown: 65506 filtered tcp ports (no-response)
Some closed ports may be reported as filtered due to --defeat-rst-ratelimit
PORT     STATE SERVICE
22/tcp   open  ssh
53/tcp   open  domain
88/tcp   open  kerberos-sec
135/tcp  open  msrpc
139/tcp  open  netbios-ssn
389/tcp  open  ldap
443/tcp  open  https
445/tcp  open  microsoft-ds
464/tcp  open  kpasswd5
593/tcp  open  http-rpc-epmap
636/tcp  open  ldapssl
1801/tcp open  msmq
2103/tcp open  zephyr-clt
2105/tcp open  eklogin
2107/tcp open  msmq-mgmt
2179/tcp open  vmrdp
3268/tcp open  globalcatLDAP
3269/tcp open  globalcatLDAPssl
3389/tcp open  ms-wbt-server
5985/tcp open  wsman
6023/tcp open  x11
6404/tcp open  boe-filesvr
6406/tcp open  boe-processsvr
6407/tcp open  boe-resssvr1
6409/tcp open  boe-resssvr3
6613/tcp open  unknown
6618/tcp open  unknown
8080/tcp open  http-proxy
9389/tcp open  adws

Nmap done: 1 IP address (1 host up) scanned in 55.84 seconds

```