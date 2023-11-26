```
Nmap scan report for 192.168.247.191
Host is up (0.050s latency).

PORT      STATE SERVICE       VERSION
80/tcp    open  http          Microsoft IIS httpd 10.0
|_http-title: 401 - Unauthorized: Access is denied due to invalid credentials.
| http-auth: 
| HTTP/1.1 401 Unauthorized\x0D
|_  Basic realm=192.168.247.191
|_http-server-header: Microsoft-IIS/10.0
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios-ssn   Microsoft Windows netbios-ssn
445/tcp   open  microsoft-ds?
3389/tcp  open  ms-wbt-server Microsoft Terminal Services
| ssl-cert: OpenSSL required to parse certificate.
| -----BEGIN CERTIFICATE-----
| MIIC4jCCAcqgAwIBAgIQVet0fmMzgJRM2u+cAdlHUzANBgkqhkiG9w0BAQsFADAa
| MRgwFgYDVQQDEw9sb2dpbi5yZWxpYS5jb20wHhcNMjMwOTI2MDEwNzI5WhcNMjQw
| MzI3MDEwNzI5WjAaMRgwFgYDVQQDEw9sb2dpbi5yZWxpYS5jb20wggEiMA0GCSqG
| SIb3DQEBAQUAA4IBDwAwggEKAoIBAQCktedEFls4QtVaGctKRDyxUHS8nY7NmEiY
| le+ybNIQaNcpwPb9XDqgzutmE4V26Acg4GKGz4nPvN+mbDBkX0vsQM9s2Ozxj3mW
| 8oIB8VqEH0U1JWFfgi9HuKucieDKk38U1oThxCZNUI6f9fH2qfVoGHYGVzZ0HRZM
| kHRejbpvve6CX8lIdSfKbSp+QrIuagE4EzaZ6je3+oGlO6B2MLM93kSOiskhKDq5
| PDiAIaKzQ3anbpMAYVXBahhmaxxcn9yXEsh+c5e+vFCi/+JTJsmO0s6alngHO7Qs
| 4Jp4DtfEXLRdPee/X0X2HRW2W4NIU/bxekeQEvyUG6tgugTTT7K5AgMBAAGjJDAi
| MBMGA1UdJQQMMAoGCCsGAQUFBwMBMAsGA1UdDwQEAwIEMDANBgkqhkiG9w0BAQsF
| AAOCAQEAQU+j7U4R6lnpouzcwg25T0pFPKPokJR+CNdnt1wjHdOnUx30P4i5gDlH
| mUDt68UfT1COYHBO7EXsr1h/XTBQujFPlIJ7yebQHXOXakbGTUFPBHAU1aRSAIGI
| K1XH1X5WxHEh4Vuz2Zz7CppnA0YDTtzwXuFQNWhGsn1ebX+SzvLQi2PmZU5o2jEb
| muqj1pU72dZIW3sKHQK9CcpE4sAWgGKP3cPrxhh2IIsIe229P8SeMbKxkBrutVID
| buIK8fX4edcPZdULZ6VezRrItHuQ2gX/NQMcV7bduOdzeUs933nlupc4tdlDM6M5
| 21p3K50BGDXaX3dbUwXdBEkwR9WfqA==
|_-----END CERTIFICATE-----
|_ssl-known-key: ERROR: Script execution failed (use -d to debug)
|_ssl-date: 2023-11-26T17:15:05+00:00; +1s from scanner time.
5985/tcp  open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-title: Not Found
|_http-server-header: Microsoft-HTTPAPI/2.0
47001/tcp open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Not Found
49664/tcp open  msrpc         Microsoft Windows RPC
49665/tcp open  msrpc         Microsoft Windows RPC
49666/tcp open  msrpc         Microsoft Windows RPC
49667/tcp open  msrpc         Microsoft Windows RPC
49668/tcp open  msrpc         Microsoft Windows RPC
49669/tcp open  msrpc         Microsoft Windows RPC
49670/tcp open  msrpc         Microsoft Windows RPC
49671/tcp open  msrpc         Microsoft Windows RPC
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: general purpose
Running (JUST GUESSING): Microsoft Windows 2022 (87%)
Aggressive OS guesses: Microsoft Windows Server 2022 (87%)
No exact OS matches for host (test conditions non-ideal).
Network Distance: 4 hops
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

Host script results:
| smb2-time: 
|   date: 2023-11-26T17:14:58
|_  start_date: N/A
| smb2-security-mode: 
|   3:1:1: 
|_    Message signing enabled but not required

TRACEROUTE (using proto 1/icmp)
HOP RTT      ADDRESS
1   49.39 ms 192.168.45.1
2   49.37 ms 192.168.45.254
3   49.70 ms 192.168.251.1
4   49.83 ms 192.168.247.191

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 69.03 seconds
```