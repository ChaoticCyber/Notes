```
Nmap scan report for 10.7.0.134
Host is up (0.00028s latency).

PORT      STATE SERVICE            VERSION
7/tcp     open  echo
9/tcp     open  discard?
13/tcp    open  daytime            Microsoft Windows USA daytime
17/tcp    open  qotd               Windows qotd (English)
19/tcp    open  chargen
135/tcp   open  msrpc              Microsoft Windows RPC
139/tcp   open  netbios-ssn        Microsoft Windows netbios-ssn
445/tcp   open  microsoft-ds       Windows 7 Professional 7601 Service Pack 1 microsoft-ds (workgroup: SUPERCORP)
3389/tcp  open  ssl/ms-wbt-server?
| rdp-ntlm-info: 
|   Target_Name: SUPERCORP
|   NetBIOS_Domain_Name: SUPERCORP
|   NetBIOS_Computer_Name: GMTARKINPC
|   DNS_Domain_Name: supercorp.local
|   DNS_Computer_Name: GMTarkinPC.supercorp.local
|   DNS_Tree_Name: supercorp.local
|   Product_Version: 6.1.7601
|_  System_Time: 2023-11-28T14:58:44+00:00
|_ssl-date: 2023-11-28T14:58:58+00:00; +36m28s from scanner time.
| ssl-cert: Subject: commonName=GMTarkinPC.supercorp.local
| Not valid before: 2023-11-26T19:27:48
|_Not valid after:  2024-05-27T19:27:48
5357/tcp  open  http               Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-title: Service Unavailable
|_http-server-header: Microsoft-HTTPAPI/2.0
5985/tcp  open  http               Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
47001/tcp open  http               Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-title: Not Found
|_http-server-header: Microsoft-HTTPAPI/2.0
49152/tcp open  msrpc              Microsoft Windows RPC
49153/tcp open  msrpc              Microsoft Windows RPC
49154/tcp open  msrpc              Microsoft Windows RPC
49155/tcp open  msrpc              Microsoft Windows RPC
49156/tcp open  msrpc              Microsoft Windows RPC
49304/tcp open  msrpc              Microsoft Windows RPC
MAC Address: 00:0C:29:A2:3A:DA (VMware)
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: general purpose
Running: Microsoft Windows 7|2008|8.1
OS CPE: cpe:/o:microsoft:windows_7::- cpe:/o:microsoft:windows_7::sp1 cpe:/o:microsoft:windows_server_2008::sp1 cpe:/o:microsoft:windows_server_2008:r2 cpe:/o:microsoft:windows_8 cpe:/o:microsoft:windows_8.1
OS details: Microsoft Windows 7 SP0 - SP1, Windows Server 2008 SP1, Windows Server 2008 R2, Windows 8, or Windows 8.1 Update 1
Network Distance: 1 hop
Service Info: Host: GMTARKINPC; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb-security-mode: 
|   account_used: guest
|   authentication_level: user
|   challenge_response: supported
|_  message_signing: disabled (dangerous, but default)
| smb-os-discovery: 
|   OS: Windows 7 Professional 7601 Service Pack 1 (Windows 7 Professional 6.1)
|   OS CPE: cpe:/o:microsoft:windows_7::sp1:professional
|   Computer name: GMTarkinPC
|   NetBIOS computer name: GMTARKINPC\x00
|   Domain name: supercorp.local
|   Forest name: supercorp.local
|   FQDN: GMTarkinPC.supercorp.local
|_  System time: 2023-11-28T09:58:45-05:00
|_clock-skew: mean: 1h36m28s, deviation: 2h14m10s, median: 36m27s
| smb2-time: 
|   date: 2023-11-28T14:58:44
|_  start_date: 2023-11-28T08:07:46
|_nbstat: NetBIOS name: GMTARKINPC, NetBIOS user: <unknown>, NetBIOS MAC: 000c29a23ada (VMware)
| smb2-security-mode: 
|   210: 
|_    Message signing enabled but not required

TRACEROUTE
HOP RTT     ADDRESS
1   0.28 ms 10.7.0.134

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 173.83 seconds

```