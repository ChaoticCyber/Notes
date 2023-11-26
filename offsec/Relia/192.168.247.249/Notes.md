```
Nmap scan report for 192.168.247.249
Host is up (0.049s latency).

PORT      STATE SERVICE       VERSION
80/tcp    open  http          Microsoft IIS httpd 10.0
|_http-server-header: Microsoft-IIS/10.0
| http-methods: 
|_  Potentially risky methods: TRACE
|_http-title: IIS Windows Server
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios-ssn   Microsoft Windows netbios-ssn
445/tcp   open  microsoft-ds?
3389/tcp  open  ms-wbt-server Microsoft Terminal Services
| ssl-cert: OpenSSL required to parse certificate.
| -----BEGIN CERTIFICATE-----
| MIIC0DCCAbigAwIBAgIQFto590f/24NGrFpN4AfG4zANBgkqhkiG9w0BAQsFADAR
| MQ8wDQYDVQQDEwZMRUdBQ1kwHhcNMjMwOTI2MDQwMzQ1WhcNMjQwMzI3MDQwMzQ1
| WjARMQ8wDQYDVQQDEwZMRUdBQ1kwggEiMA0GCSqGSIb3DQEBAQUAA4IBDwAwggEK
| AoIBAQDXY6hewiuwyBXtvRSuOazmfmodU6O5KEoPehKGdRMaEbfp8MF+avu77Ont
| BIL6tf5+8gIBV53u7tT4cb46ziPWf0xVFrabZOd3D+LSmcLsniRXSUQgzBlYK/dP
| NNs3ItuybQxtCsW3mraa/U/LOHjaHYgZUoLAW5AQB809ivM7kWGtdPyJcfpSOBQh
| v84YsCgpxuetqd4j9YDSk0AwwCImZYCGRtBIRlRiGxB+qNed0o4mYwY1ZPwCIxaS
| gKljsTlUldiilDIgvo3zy3gH0ErVgwVlFmDG1vJgK3FqGXf3N/DhfKOVGIY+OOEN
| wC3OCEETmgaD/vlg6wi20pMeNIHFAgMBAAGjJDAiMBMGA1UdJQQMMAoGCCsGAQUF
| BwMBMAsGA1UdDwQEAwIEMDANBgkqhkiG9w0BAQsFAAOCAQEAMFT6lSwSTY1rvi6u
| VESifJ8CFGoNEIFcKpJWQIx9GJRHKfv+HrjUyCef7x7Py2Qf0DJjx5nM5Hc5sA1m
| rdgXNX19P4AbSRHUX6abBtuWRd/afVhe/lmvsGOx6mLUe3kvaDp5I81HxjS8fjcL
| 6ktWo3NrZH29ypsIW87pq0t50dQhcA7aOzN9jLllbEKrWkvcyxQlFxTbG/33E99I
| R/dFRrxGqUYxyXgq7eEcPJveP/+znuBQncYlURfk69uYB+V9d6Vchf3dE9DW83nd
| 6/AeAZ5Xv9JZ+ZFrmuy/PZnp4XufKAoODg5dBUCC7V6qvlXNjoVHWLxyRwYnmvVB
| 2PBG5w==
|_-----END CERTIFICATE-----
|_ssl-date: 2023-11-26T17:20:09+00:00; +1s from scanner time.
|_ssl-known-key: ERROR: Script execution failed (use -d to debug)
5985/tcp  open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-title: Not Found
|_http-server-header: Microsoft-HTTPAPI/2.0
8000/tcp  open  http          Apache httpd 2.4.54 ((Win64) OpenSSL/1.1.1p PHP/7.4.30)
|_http-server-header: Apache/2.4.54 (Win64) OpenSSL/1.1.1p PHP/7.4.30
|_http-open-proxy: Proxy might be redirecting requests
| http-title: Welcome to XAMPP
|_Requested resource was http://192.168.247.249:8000/dashboard/
47001/tcp open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
49664/tcp open  msrpc         Microsoft Windows RPC
49665/tcp open  msrpc         Microsoft Windows RPC
49666/tcp open  msrpc         Microsoft Windows RPC
49667/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49669/tcp open  msrpc         Microsoft Windows RPC
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: general purpose
Running (JUST GUESSING): Microsoft Windows 2022 (88%)
Aggressive OS guesses: Microsoft Windows Server 2022 (88%)
No exact OS matches for host (test conditions non-ideal).
Network Distance: 4 hops
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2-security-mode: 
|   3:1:1: 
|_    Message signing enabled but not required
|_clock-skew: mean: 1s, deviation: 0s, median: 0s
| smb2-time: 
|   date: 2023-11-26T17:20:05
|_  start_date: N/A

TRACEROUTE (using proto 1/icmp)
HOP RTT      ADDRESS
1   50.35 ms 192.168.45.1
2   50.40 ms 192.168.45.254
3   51.26 ms 192.168.251.1
4   51.36 ms 192.168.247.249

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 67.26 seconds
```