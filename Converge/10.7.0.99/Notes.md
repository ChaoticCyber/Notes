```
Nmap scan report for 10.7.0.99
Host is up (0.00016s latency).

PORT     STATE SERVICE VERSION
8080/tcp open  http    Apache Tomcat
|_http-open-proxy: Proxy might be redirecting requests
|_http-title: Apache Tomcat
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: general purpose
Running: Linux 2.6.X
OS CPE: cpe:/o:linux:linux_kernel:2.6.32
OS details: Linux 2.6.32
Network Distance: 0 hops

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 8.15 seconds
Starting Nmap 7.93 ( https://nmap.org ) at 2023-11-28 08:16 CST
Nmap scan report for 10.7.0.106
Host is up (0.00054s latency).

PORT      STATE SERVICE            VERSION
80/tcp    open  http               Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-title: Service Unavailable
|_http-server-header: Microsoft-HTTPAPI/2.0
135/tcp   open  msrpc              Microsoft Windows RPC
139/tcp   open  netbios-ssn        Microsoft Windows netbios-ssn
445/tcp   open  microsoft-ds       Windows 10 Education 10240 microsoft-ds (workgroup: SUPERCORP)
3389/tcp  open  ssl/ms-wbt-server?
| rdp-ntlm-info: 
|   Target_Name: SUPERCORP
|   NetBIOS_Domain_Name: SUPERCORP
|   NetBIOS_Computer_Name: DESKTOP-DOG0A1R
|   DNS_Domain_Name: supercorp.local
|   DNS_Computer_Name: DESKTOP-DOG0A1R.supercorp.local
|   DNS_Tree_Name: supercorp.local
|   Product_Version: 10.0.10240
|_  System_Time: 2023-11-28T14:49:58+00:00
|_ssl-date: 2023-11-28T14:50:05+00:00; +31m53s from scanner time.
| ssl-cert: Subject: commonName=DESKTOP-DOG0A1R.supercorp.local
| Not valid before: 2023-11-26T20:37:17
|_Not valid after:  2024-05-27T20:37:17
5985/tcp  open  http               Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
8089/tcp  open  ssl/http           Splunkd httpd
|_http-server-header: Splunkd
|_http-title: splunkd
| http-robots.txt: 1 disallowed entry 
|_/
| ssl-cert: Subject: commonName=SplunkServerDefaultCert/organizationName=SplunkUser
| Not valid before: 2019-01-19T06:33:42
|_Not valid after:  2022-01-18T06:33:42
47001/tcp open  http               Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-title: Not Found
|_http-server-header: Microsoft-HTTPAPI/2.0
49408/tcp open  msrpc              Microsoft Windows RPC
49409/tcp open  msrpc              Microsoft Windows RPC
49411/tcp open  msrpc              Microsoft Windows RPC
49412/tcp open  msrpc              Microsoft Windows RPC
49413/tcp open  msrpc              Microsoft Windows RPC
49435/tcp open  msrpc              Microsoft Windows RPC
49450/tcp open  msrpc              Microsoft Windows RPC
49487/tcp open  msrpc              Microsoft Windows RPC
MAC Address: 00:0C:29:14:99:46 (VMware)
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: general purpose
Running: Microsoft Windows 10
OS CPE: cpe:/o:microsoft:windows_10
OS details: Microsoft Windows 10 1507 - 1607
Network Distance: 1 hop
Service Info: Host: DESKTOP-DOG0A1R; OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
|_nbstat: NetBIOS name: DESKTOP-DOG0A1R, NetBIOS user: <unknown>, NetBIOS MAC: 000c29149946 (VMware)
|_clock-skew: mean: 1h31m53s, deviation: 2h14m10s, median: 31m52s
| smb-security-mode: 
|   account_used: guest
|   authentication_level: user
|   challenge_response: supported
|_  message_signing: disabled (dangerous, but default)
| smb2-time: 
|   date: 2023-11-28T14:49:58
|_  start_date: 2023-11-28T14:07:08
| smb-os-discovery: 
|   OS: Windows 10 Education 10240 (Windows 10 Education 6.3)
|   OS CPE: cpe:/o:microsoft:windows_10::-
|   Computer name: DESKTOP-DOG0A1R
|   NetBIOS computer name: DESKTOP-DOG0A1R\x00
|   Domain name: supercorp.local
|   Forest name: supercorp.local
|   FQDN: DESKTOP-DOG0A1R.supercorp.local
|_  System time: 2023-11-28T09:49:59-05:00
| smb2-security-mode: 
|   311: 
|_    Message signing enabled but not required

TRACEROUTE
HOP RTT     ADDRESS
1   0.54 ms 10.7.0.106

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 74.74 seconds
```