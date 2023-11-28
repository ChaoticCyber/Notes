```
Nmap scan report for 10.7.0.8
Host is up (0.00023s latency).

PORT      STATE SERVICE            VERSION
135/tcp   open  msrpc              Microsoft Windows RPC
139/tcp   open  netbios-ssn        Microsoft Windows netbios-ssn
445/tcp   open  microsoft-ds       Microsoft Windows Server 2008 R2 - 2012 microsoft-ds
3389/tcp  open  ssl/ms-wbt-server?
|_ssl-date: 2023-11-28T14:53:07+00:00; +36m29s from scanner time.
| ssl-cert: Subject: commonName=sqldata01.supercorp.local
| Not valid before: 2023-11-26T20:08:27
|_Not valid after:  2024-05-27T20:08:27
| rdp-ntlm-info: 
|   Target_Name: SUPERCORP
|   NetBIOS_Domain_Name: SUPERCORP
|   NetBIOS_Computer_Name: SQLDATA01
|   DNS_Domain_Name: supercorp.local
|   DNS_Computer_Name: sqldata01.supercorp.local
|   DNS_Tree_Name: supercorp.local
|   Product_Version: 6.3.9600
|_  System_Time: 2023-11-28T14:53:02+00:00
5985/tcp  open  http               Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
47001/tcp open  http               Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
49152/tcp open  msrpc              Microsoft Windows RPC
49153/tcp open  msrpc              Microsoft Windows RPC
49154/tcp open  msrpc              Microsoft Windows RPC
49155/tcp open  msrpc              Microsoft Windows RPC
49156/tcp open  msrpc              Microsoft Windows RPC
49194/tcp open  msrpc              Microsoft Windows RPC
49203/tcp open  msrpc              Microsoft Windows RPC
49221/tcp open  msrpc              Microsoft Windows RPC
MAC Address: 00:0C:29:4B:03:8B (VMware)
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: general purpose
Running: Microsoft Windows 2012|7|8.1
OS CPE: cpe:/o:microsoft:windows_server_2012:r2 cpe:/o:microsoft:windows_7:::ultimate cpe:/o:microsoft:windows_8.1
OS details: Microsoft Windows Server 2012 R2 Update 1, Microsoft Windows 7, Windows Server 2012, or Windows 8.1 Update 1
Network Distance: 1 hop
Service Info: OSs: Windows, Windows Server 2008 R2 - 2012; CPE: cpe:/o:microsoft:windows

Host script results:
|_nbstat: NetBIOS name: SQLDATA01, NetBIOS user: <unknown>, NetBIOS MAC: 000c294b038b (VMware)
| smb2-security-mode: 
|   302: 
|_    Message signing enabled but not required
|_clock-skew: mean: 36m28s, deviation: 0s, median: 36m28s
| smb2-time: 
|   date: 2023-11-28T14:53:01
|_  start_date: 2023-11-27T20:10:00
| smb-security-mode: 
|   account_used: <blank>
|   authentication_level: user
|   challenge_response: supported
|_  message_signing: disabled (dangerous, but default)

TRACEROUTE
HOP RTT     ADDRESS
1   0.23 ms 10.7.0.8

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 72.44 seconds
```