```
Starting Nmap 7.94 ( https://nmap.org ) at 2023-11-26 12:15 EST
Nmap scan report for 192.168.247.246
Host is up (0.050s latency).

PORT     STATE SERVICE VERSION
80/tcp   open  http    Apache httpd 2.4.52 ((Ubuntu))
|_http-server-header: Apache/2.4.52 (Ubuntu)
|_http-title: Code Validation
443/tcp  open  ssl
| tls-alpn: 
|_  http/1.1
|_ip-https-discover: ERROR: Script execution failed (use -d to debug)
|_http-server-header: Apache/2.4.52 (Ubuntu)
|_ssl-known-key: ERROR: Script execution failed (use -d to debug)
| ssl-cert: OpenSSL required to parse certificate.
| -----BEGIN CERTIFICATE-----
| MIIC6TCCAdGgAwIBAgIUIN3Z/giwrWikVN/gzzofa98CJ1AwDQYJKoZIhvcNAQEL
| BQAwDzENMAsGA1UEAwwEZGVtbzAeFw0yMjEwMTIwNzQ2MjdaFw0zMjEwMDkwNzQ2
| MjdaMA8xDTALBgNVBAMMBGRlbW8wggEiMA0GCSqGSIb3DQEBAQUAA4IBDwAwggEK
| AoIBAQCMPw2+IkC55uip8gDmvy+mN/FtQJBck6audIht6POsdrE2GzfhAoxZY9al
| XkTc3WPOxP2X1I4ea1t1y8SQuX7jomUlNOgkGtVbj+RYzU8Qau7XWSTBMbVkRluc
| B+w5vPsGL1XGMd35V7Td6ZhotXLwc0j19smwewETujURfSmGCKdwbHztKozyW9Qg
| QFOtNI4gOHpvMxTYpR3QDkBYvIzaH+FaU8xqrr/GJiFSz8MUhxVPSM2QyqSmsFyE
| HYijIDbxBNRyf1lAmReLdwpwGqpRvBF1wYfpYyTvjW/j0LQPfvCcCVxD1v/3N3oK
| VR4/EYqBrCr9umF7Q3w5E4hC0x5VAgMBAAGjPTA7MAkGA1UdEwQCMAAwDwYDVR0R
| BAgwBoIEZGVtbzAdBgNVHQ4EFgQUqWpscb2cgQbMGE4Nh4vVDLAs55EwDQYJKoZI
| hvcNAQELBQADggEBACvVHEqW54LzwFNKfLMlbbrSitnXhGc1zgOaYdBnF95weO3j
| 5gEbGNElednFgWQEZzLz5ruS9i0aiKsQYKuh+AL+QQRdycfCbTxDVTopO9sxFYGd
| UpSxCGToYe5JULiNpnBpTWPEldc608y2jhpJpsH5UGifvRp/VpHW/3A+9t8oAUeN
| /SVW3bQ7sLEEvCmHH4E1uJS3k6kBidDY1A9OOxaL0k2v/cB8PONnEMwP4DcmKRA1
| cVrgXiR8x7E5zcVUPj8cM5+DqSOQTAphAcVbVx2c/K2XMENFZqVUbRFbuZSXVExp
| TQICNlWeutzCZGE7rREsIUUIigT9erEAvTu28RI=
|_-----END CERTIFICATE-----
|_ssl-date: TLS randomness does not represent time
|_http-title: 400 Bad Request
2222/tcp open  ssh     OpenSSH 8.9p1 Ubuntu 3 (Ubuntu Linux; protocol 2.0)
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Aggressive OS guesses: Linux 2.6.18 (87%), Linux 4.15 - 5.8 (87%), Linux 5.0 - 5.4 (87%), Linux 2.6.32 (87%), Linux 2.6.32 or 3.10 (87%), Linux 3.5 (87%), Linux 4.4 (87%), WatchGuard Fireware 11.8 (87%), Linux 5.3 - 5.4 (87%), Linux 4.8 (86%)
No exact OS matches for host (test conditions non-ideal).
Network Distance: 4 hops
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel

TRACEROUTE (using proto 1/icmp)
HOP RTT      ADDRESS
1   46.91 ms 192.168.45.1
2   46.88 ms 192.168.45.254
3   47.72 ms 192.168.251.1
4   47.81 ms 192.168.247.246

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 13.88 seconds
```