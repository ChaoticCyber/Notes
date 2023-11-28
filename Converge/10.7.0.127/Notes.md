```
Nmap scan report for 10.7.0.127
Host is up (0.00044s latency).

PORT      STATE SERVICE       VERSION
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios-ssn   Microsoft Windows netbios-ssn
445/tcp   open  microsoft-ds?
3389/tcp  open  ms-wbt-server Microsoft Terminal Services
| ssl-cert: Subject: commonName=Yavin4.supercorp.local
| Not valid before: 2023-11-26T20:11:37
|_Not valid after:  2024-05-27T20:11:37
| rdp-ntlm-info: 
|   Target_Name: SUPERCORP
|   NetBIOS_Domain_Name: SUPERCORP
|   NetBIOS_Computer_Name: YAVIN4
|   DNS_Domain_Name: supercorp.local
|   DNS_Computer_Name: Yavin4.supercorp.local
|   Product_Version: 10.0.17763
|_  System_Time: 2023-11-28T14:55:54+00:00
|_ssl-date: 2023-11-28T14:55:59+00:00; +36m35s from scanner time.
5985/tcp  open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-title: Not Found
|_http-server-header: Microsoft-HTTPAPI/2.0
47001/tcp open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-title: Not Found
|_http-server-header: Microsoft-HTTPAPI/2.0
49664/tcp open  msrpc         Microsoft Windows RPC
49665/tcp open  msrpc         Microsoft Windows RPC
49667/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49674/tcp open  msrpc         Microsoft Windows RPC
49676/tcp open  msrpc         Microsoft Windows RPC
49677/tcp open  msrpc         Microsoft Windows RPC
49694/tcp open  msrpc         Microsoft Windows RPC
49729/tcp open  msrpc         Microsoft Windows RPC
MAC Address: 00:0C:29:DA:5F:D3 (VMware)
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Aggressive OS guesses: Microsoft Windows 10 1709 - 1909 (97%), Microsoft Windows 10 1709 - 1803 (94%), Microsoft Windows Longhorn (92%), Microsoft Windows Server 2012 (92%), Microsoft Windows Vista SP1 (92%), Microsoft Windows Server 2016 build 10586 - 14393 (91%), Microsoft Windows 7, Windows Server 2012, or Windows 8.1 Update 1 (91%), Microsoft Windows 10 1703 (91%), Microsoft Windows 10 1809 - 1909 (91%), Microsoft Windows Server 2012 R2 (91%)
No exact OS matches for host (test conditions non-ideal).
Network Distance: 1 hop
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2-time: 
|   date: 2023-11-28T14:55:54
|_  start_date: N/A
|_nbstat: NetBIOS name: YAVIN4, NetBIOS user: <unknown>, NetBIOS MAC: 000c29da5fd3 (VMware)
| smb2-security-mode: 
|   311: 
|_    Message signing enabled but not required
|_clock-skew: mean: 36m35s, deviation: 0s, median: 36m34s

TRACEROUTE
HOP RTT     ADDRESS
1   0.44 ms 10.7.0.127

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 63.07 seconds
```



