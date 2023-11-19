```
MariaDB [hospital]> select * from users;
+----+----------+--------------------------------------------------------------+---------------------+
| id | username | password                                                     | created_at          |
+----+----------+--------------------------------------------------------------+---------------------+
|  1 | admin    | $2y$10$caGIEbf9DBF7ddlByqCkrexkt0cPseJJ5FiVO1cnhG.3NLrxcjMh2 | 2023-09-21 14:46:04 |
|  2 | patient  | $2y$10$a.lNstD7JdiNYxEepKf1/OZ5EM5wngYrf.m5RxXCgSud7MVU6/tgO | 2023-09-21 15:35:11 |
|  3 | asdf     | $2y$10$Bj1q5wwelZa5xhXcxHhL7evnegQlTc12Eqa5lMVW6FTc2It2zlxse | 2023-11-20 03:41:33 |
+----+----------+--------------------------------------------------------------+---------------------+
3 rows in set (0.001 sec)

MariaDB [hospital]> 
```