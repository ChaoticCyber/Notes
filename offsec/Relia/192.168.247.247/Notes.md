```
Nmap scan report for 192.168.247.247
Host is up (0.049s latency).

PORT      STATE SERVICE       VERSION
80/tcp    open  http          Apache httpd 2.4.54 ((Win64) OpenSSL/1.1.1p PHP/8.1.10)
|_http-title: RELIA - New Hire Information
|_http-server-header: Apache/2.4.54 (Win64) OpenSSL/1.1.1p PHP/8.1.10
135/tcp   open  msrpc         Microsoft Windows RPC
139/tcp   open  netbios-ssn   Microsoft Windows netbios-ssn
443/tcp   open  ssl
| ssl-cert: OpenSSL required to parse certificate.
| -----BEGIN CERTIFICATE-----
| MIIBnzCCAQgCCQC1x1LJh4G1AzANBgkqhkiG9w0BAQUFADAUMRIwEAYDVQQDEwls
| b2NhbGhvc3QwHhcNMDkxMTEwMjM0ODQ3WhcNMTkxMTA4MjM0ODQ3WjAUMRIwEAYD
| VQQDEwlsb2NhbGhvc3QwgZ8wDQYJKoZIhvcNAQEBBQADgY0AMIGJAoGBAMEl0yfj
| 7K0Ng2pt51+adRAj4pCdoGOVjx1BmljVnGOMW3OGkHnMw9ajibh1vB6UfHxu463o
| J1wLxgxq+Q8y/rPEehAjBCspKNSq+bMvZhD4p8HNYMRrKFfjZzv3ns1IItw46kgT
| gDpAl1cMRzVGPXFimu5TnWMOZ3ooyaQ0/xntAgMBAAEwDQYJKoZIhvcNAQEFBQAD
| gYEAavHzSWz5umhfb/MnBMa5DL2VNzS+9whmmpsDGEG+uR0kM1W2GQIdVHHJTyFd
| aHXzgVJBQcWTwhp84nvHSiQTDBSaT6cQNQpvag/TaED/SEQpm0VqDFwpfFYuufBL
| vVNbLkKxbK2XwUvu0RxoLdBMC/89HqrZ0ppiONuQ+X2MtxE=
|_-----END CERTIFICATE-----
| tls-alpn: 
|_  http/1.1
|_ip-https-discover: ERROR: Script execution failed (use -d to debug)
|_ssl-known-key: ERROR: Script execution failed (use -d to debug)
|_http-server-header: Apache/2.4.54 (Win64) OpenSSL/1.1.1p PHP/8.1.10
|_ssl-date: TLS randomness does not represent time
|_http-title: 400 Bad Request
445/tcp   open  microsoft-ds?
3389/tcp  open  ms-wbt-server Microsoft Terminal Services
|_ssl-known-key: ERROR: Script execution failed (use -d to debug)
| ssl-cert: OpenSSL required to parse certificate.
| -----BEGIN CERTIFICATE-----
| MIICzjCCAbagAwIBAgIQRYaXUio0DZdBNtVcIMpAXjANBgkqhkiG9w0BAQsFADAQ
| MQ4wDAYDVQQDEwVXRUIwMjAeFw0yMzA5MjYwMzI5NTNaFw0yNDAzMjcwMzI5NTNa
| MBAxDjAMBgNVBAMTBVdFQjAyMIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKC
| AQEA7yA5nw0ebJVv73IB0F7dUnZQjL0Ookdu+smsK9L996iL6yu1rB/AUu3Fs65a
| +VeolxK3/pBVdnNod+ZuGjAJr/iwtCB+7TMXJe87aijykgN4J4xarzlhdlDRg+81
| XRuSqTWOuet9/0b7crbi5K/XWews/UrrmA9fnsfoelkKx/GVR9ObCIupzDAi1yNP
| y1C4iPh1EkOAPP2XTrNQmwKi2VISoi6baHZO8/4B8HNMlbVKgZlX+19xl4MIJL8j
| 2YYRq/dzBve4lGTbgZYncYNQdSIYxc3VXDJgiDl5EJiHD7vW1IM07f2F1Ug8ZIRR
| axSzaO+vjy64uc5TmHIeXsp1MQIDAQABoyQwIjATBgNVHSUEDDAKBggrBgEFBQcD
| ATALBgNVHQ8EBAMCBDAwDQYJKoZIhvcNAQELBQADggEBAEzHF4vH/uBor6eKYLJC
| Fg5sU8GEfOx5RdYJy/1R3OfjK1F7gu4aRhgScY13wxCk6OXU8LMmPhY/KPPnOUzc
| CDcHaDp7umTC8ElsA5cnqb8DmZVCJyU6kUg2QxdJrNAD2gVsAaeJGtn01Oy9QtXO
| chITUh75F74lus5VGc3FGksyluOkow/uVztMKAD6h/kj0jJfHj5O5BdkiB2zLkZt
| Y/APjBDe7eTiToTuvu3w7aH33Fk6YTd6CQQH1a6ZV6zBXwBlzf0EHWGTAlSbwRIU
| CStc0ET4f4ZYolRggMdg6vVSe+Ee5q0HRxZb25MbmwadkiN75xe4H8Y88yb7On5Z
| sdQ=
|_-----END CERTIFICATE-----
|_ssl-date: 2023-11-26T17:17:26+00:00; +1s from scanner time.
5985/tcp  open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-title: Not Found
|_http-server-header: Microsoft-HTTPAPI/2.0
14020/tcp open  ftp           FileZilla ftpd
|_ftp-bounce: bounce working!
| ftp-anon: Anonymous FTP login allowed (FTP code 230)
|_-r--r--r-- 1 ftp ftp         237639 Nov 04  2022 umbraco.pdf
| ftp-syst: 
|_  SYST: UNIX emulated by FileZilla
14080/tcp open  http          Microsoft HTTPAPI httpd 2.0 (SSDP/UPnP)
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Bad Request
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
| smb2-time: 
|   date: 2023-11-26T17:17:19
|_  start_date: N/A

TRACEROUTE (using proto 1/icmp)
HOP RTT      ADDRESS
1   46.99 ms 192.168.45.1
2   46.96 ms 192.168.45.254
3   47.97 ms 192.168.251.1
4   48.06 ms 192.168.247.247

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 68.90 seconds

```