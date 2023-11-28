```
Nmap scan report for 10.7.0.6
Host is up (0.00023s latency).

PORT      STATE SERVICE            VERSION
111/tcp   open  rpcbind            2-4 (RPC #100000)
| rpcinfo: 
|   program version    port/proto  service
|   100000  2,3,4        111/tcp   rpcbind
|   100000  2,3,4        111/tcp6  rpcbind
|   100000  2,3,4        111/udp   rpcbind
|   100000  2,3,4        111/udp6  rpcbind
|   100003  2,3         2049/tcp   nfs
|   100003  2,3         2049/tcp6  nfs
|   100003  2,3         2049/udp   nfs
|   100003  2,3         2049/udp6  nfs
|   100005  1,2,3       1048/tcp   mountd
|   100005  1,2,3       1048/tcp6  mountd
|   100005  1,2,3       1048/udp   mountd
|   100005  1,2,3       1048/udp6  mountd
|   100021  1,2,3,4     1047/tcp   nlockmgr
|   100021  1,2,3,4     1047/tcp6  nlockmgr
|   100021  1,2,3,4     1047/udp   nlockmgr
|   100021  1,2,3,4     1047/udp6  nlockmgr
|   100024  1           1039/tcp   status
|   100024  1           1039/tcp6  status
|   100024  1           1039/udp   status
|_  100024  1           1039/udp6  status
135/tcp   open  msrpc              Microsoft Windows RPC
139/tcp   open  netbios-ssn        Microsoft Windows netbios-ssn
445/tcp   open  microsoft-ds       Windows Server 2008 R2 Standard 7601 Service Pack 1 microsoft-ds (workgroup: SUPERCORP)
1039/tcp  open  status             1 (RPC #100024)
1047/tcp  open  nlockmgr           1-4 (RPC #100021)
1048/tcp  open  mountd             1-3 (RPC #100005)
2049/tcp  open  nfs                2-3 (RPC #100003)
3205/tcp  open  isns?
3389/tcp  open  ssl/ms-wbt-server?
|_ssl-date: 2023-11-28T14:43:30+00:00; +32m25s from scanner time.
| ssl-cert: Subject: commonName=dfs.supercorp.local
| Not valid before: 2023-11-26T19:58:39
|_Not valid after:  2024-05-27T19:58:39
| rdp-ntlm-info: 
|   Target_Name: SUPERCORP
|   NetBIOS_Domain_Name: SUPERCORP
|   NetBIOS_Computer_Name: DFS
|   DNS_Domain_Name: supercorp.local
|   DNS_Computer_Name: dfs.supercorp.local
|   DNS_Tree_Name: supercorp.local
|   Product_Version: 6.1.7601
|_  System_Time: 2023-11-28T14:43:24+00:00
5985/tcp  open  http               Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
8089/tcp  open  ssl/http           Splunkd httpd
|_http-server-header: Splunkd
| ssl-cert: Subject: commonName=SplunkServerDefaultCert/organizationName=SplunkUser
| Not valid before: 2019-01-19T19:03:49
|_Not valid after:  2022-01-18T19:03:49
| http-robots.txt: 1 disallowed entry 
|_/
|_http-title: splunkd
47001/tcp open  http               Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
49152/tcp open  msrpc              Microsoft Windows RPC
49153/tcp open  msrpc              Microsoft Windows RPC
49154/tcp open  msrpc              Microsoft Windows RPC
49185/tcp open  msrpc              Microsoft Windows RPC
49219/tcp open  msrpc              Microsoft Windows RPC
49223/tcp open  msrpc              Microsoft Windows RPC
MAC Address: 00:0C:29:99:9C:8C (VMware)
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: general purpose
Running: Microsoft Windows 7|2008|8.1
OS CPE: cpe:/o:microsoft:windows_7::- cpe:/o:microsoft:windows_7::sp1 cpe:/o:microsoft:windows_server_2008::sp1 cpe:/o:microsoft:windows_server_2008:r2 cpe:/o:microsoft:windows_8 cpe:/o:microsoft:windows_8.1
OS details: Microsoft Windows 7 SP0 - SP1, Windows Server 2008 SP1, Windows Server 2008 R2, Windows 8, or Windows 8.1 Update 1
Network Distance: 1 hop
Service Info: Host: DFS; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb-security-mode: 
|   account_used: guest
|   authentication_level: user
|   challenge_response: supported
|_  message_signing: disabled (dangerous, but default)
|_clock-skew: mean: 1h32m25s, deviation: 2h14m10s, median: 32m25s
| smb-os-discovery: 
|   OS: Windows Server 2008 R2 Standard 7601 Service Pack 1 (Windows Server 2008 R2 Standard 6.1)
|   OS CPE: cpe:/o:microsoft:windows_server_2008::sp1
|   Computer name: dfs
|   NetBIOS computer name: DFS\x00
|   Domain name: supercorp.local
|   Forest name: supercorp.local
|   FQDN: dfs.supercorp.local
|_  System time: 2023-11-28T09:43:24-05:00
|_nbstat: NetBIOS name: DFS, NetBIOS user: <unknown>, NetBIOS MAC: 000c29999c8c (VMware)
| smb2-time: 
|   date: 2023-11-28T14:43:24
|_  start_date: 2023-11-27T19:58:26
| smb2-security-mode: 
|   210: 
|_    Message signing enabled but not required

TRACEROUTE
HOP RTT     ADDRESS
1   0.23 ms 10.7.0.6

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 89.48 seconds
```