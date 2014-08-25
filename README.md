ml
==

编辑my.ini， [mysqld]下面一行，增加如下内容：

explicit_defaults_for_timestamp=true

cmd里面执行：
mysqld --remove mysql

mysqld --install mysql --defaults-file="C:\Program Files\MySQL\MySQL Server 5.6\my.ini"

net start mysql

mysql -u root 
