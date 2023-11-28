```
Nmap scan report for 10.7.0.5
Host is up (0.00042s latency).

PORT      STATE SERVICE       VERSION
53/tcp    open  domain        Simple DNS Plus
80/tcp    open  http          Microsoft IIS httpd 10.0
|_http-server-header: Microsoft-IIS/10.0
|_http-title: IIS Windows Server
| http-methods: 
|_  Potentially risky methods: TRACE
88/tcp    open  kerberos-sec  Microsoft Windows Kerberos (server time: 2023-11-28 14:44:46Z)
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios-ssn   Microsoft Windows netbios-ssn
389/tcp   open  ldap          Microsoft Windows Active Directory LDAP (Domain: supercorp.local0., Site: Default-First-Site-Name)
|_ssl-date: 2023-11-28T14:45:51+00:00; +36m28s from scanner time.
| ssl-cert: Subject: commonName=dc1.supercorp.local
| Subject Alternative Name: othername: 1.3.6.1.4.1.311.25.1::<unsupported>, DNS:dc1.supercorp.local
| Not valid before: 2023-11-27T19:51:29
|_Not valid after:  2024-11-26T19:51:29
443/tcp   open  ssl/http      Microsoft IIS httpd 10.0
| tls-alpn: 
|_  http/1.1
|_ssl-date: 2023-11-28T14:45:51+00:00; +36m28s from scanner time.
|_http-server-header: Microsoft-IIS/10.0
| ssl-cert: Subject: commonName=supercorp-DC1-CA
| Not valid before: 2021-09-15T21:07:12
|_Not valid after:  2031-09-15T21:17:10
| http-methods: 
|_  Potentially risky methods: TRACE
|_http-title: IIS Windows Server
445/tcp   open  microsoft-ds?
464/tcp   open  kpasswd5?
593/tcp   open  ncacn_http    Microsoft Windows RPC over HTTP 1.0
636/tcp   open  ssl/ldap      Microsoft Windows Active Directory LDAP (Domain: supercorp.local0., Site: Default-First-Site-Name)
| ssl-cert: Subject: commonName=dc1.supercorp.local
| Subject Alternative Name: othername: 1.3.6.1.4.1.311.25.1::<unsupported>, DNS:dc1.supercorp.local
| Not valid before: 2023-11-27T19:51:29
|_Not valid after:  2024-11-26T19:51:29
|_ssl-date: 2023-11-28T14:45:51+00:00; +36m28s from scanner time.
3268/tcp  open  ldap          Microsoft Windows Active Directory LDAP (Domain: supercorp.local0., Site: Default-First-Site-Name)
|_ssl-date: 2023-11-28T14:45:51+00:00; +36m28s from scanner time.
| ssl-cert: Subject: commonName=dc1.supercorp.local
| Subject Alternative Name: othername: 1.3.6.1.4.1.311.25.1::<unsupported>, DNS:dc1.supercorp.local
| Not valid before: 2023-11-27T19:51:29
|_Not valid after:  2024-11-26T19:51:29
3269/tcp  open  ssl/ldap      Microsoft Windows Active Directory LDAP (Domain: supercorp.local0., Site: Default-First-Site-Name)
|_ssl-date: 2023-11-28T14:45:51+00:00; +36m28s from scanner time.
| ssl-cert: Subject: commonName=dc1.supercorp.local
| Subject Alternative Name: othername: 1.3.6.1.4.1.311.25.1::<unsupported>, DNS:dc1.supercorp.local
| Not valid before: 2023-11-27T19:51:29
|_Not valid after:  2024-11-26T19:51:29
3389/tcp  open  ms-wbt-server Microsoft Terminal Services
| ssl-cert: Subject: commonName=DC1.supercorp.local
| Not valid before: 2023-11-26T19:52:40
|_Not valid after:  2024-05-27T19:52:40
|_ssl-date: 2023-11-28T14:45:51+00:00; +36m28s from scanner time.
5357/tcp  open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Service Unavailable
5985/tcp  open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
9389/tcp  open  mc-nmf        .NET Message Framing
47001/tcp open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
49664/tcp open  msrpc         Microsoft Windows RPC
49665/tcp open  msrpc         Microsoft Windows RPC
49666/tcp open  msrpc         Microsoft Windows RPC
49667/tcp open  msrpc         Microsoft Windows RPC
49669/tcp open  msrpc         Microsoft Windows RPC
49670/tcp open  msrpc         Microsoft Windows RPC
49671/tcp open  ncacn_http    Microsoft Windows RPC over HTTP 1.0
49672/tcp open  msrpc         Microsoft Windows RPC
49674/tcp open  msrpc         Microsoft Windows RPC
49679/tcp open  msrpc         Microsoft Windows RPC
49690/tcp open  msrpc         Microsoft Windows RPC
49696/tcp open  msrpc         Microsoft Windows RPC
59078/tcp open  msrpc         Microsoft Windows RPC
MAC Address: 00:0C:29:29:88:27 (VMware)
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Aggressive OS guesses: Microsoft Windows 10 1709 - 1909 (97%), Microsoft Windows 10 1709 - 1803 (94%), Microsoft Windows Server 2012 (93%), Microsoft Windows Longhorn (92%), Microsoft Windows Vista SP1 (92%), Microsoft Windows Server 2012 R2 Update 1 (91%), Microsoft Windows Server 2016 build 10586 - 14393 (91%), Microsoft Windows 7, Windows Server 2012, or Windows 8.1 Update 1 (91%), Microsoft Windows 10 1703 (91%), Microsoft Windows 10 1809 - 1909 (91%)
No exact OS matches for host (test conditions non-ideal).
Network Distance: 1 hop
Service Info: Host: DC1; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
|_nbstat: NetBIOS name: DC1, NetBIOS user: <unknown>, NetBIOS MAC: 000c29298827 (VMware)
|_clock-skew: mean: 36m27s, deviation: 0s, median: 36m27s
| smb2-time: 
|   date: 2023-11-28T14:45:43
|_  start_date: N/A
| smb2-security-mode: 
|   311: 
|_    Message signing enabled and required

TRACEROUTE
HOP RTT     ADDRESS
1   0.42 ms 10.7.0.5

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 71.95 seconds
```