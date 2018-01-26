# lnmp1.4
> lnmp环境

### 目录介绍
1. php 目录：PHP相关配置、扩展存放目录
2. nginx：Nginx配置、虚拟主机存放目录
3. mysql：mysql 配置数据等目录

### 软件版本
* PHP：5.6.31
* MySQL：5.5.42
* Nginx：1.8.0
* Linux：CentOS 7

### 账号信息
* MySQL：root/123456

### LNMP相关软件安装目录
* Nginx 目录: /usr/local/nginx/
* MySQL 目录 : /usr/local/mysql/
* MySQL数据库所在目录：/usr/local/mysql/var/
* MariaDB 目录 : /usr/local/mariadb/
* MariaDB数据库所在目录：/usr/local/mariadb/var/
* PHP目录 : /usr/local/php/
* 多PHP版本目录 : /usr/local/php5.5/ 其他版本前面5.5的版本号换成其他即可
* PHPMyAdmin目录 : 1.0及以后版本为 /home/wwwroot/default/phpmyadmin/ 强烈建议将此目录重命名为其不容易猜到的名字。phpmyadmin可自己从官网下载新版替换。
* 默认网站目录 : /home/wwwroot/default/
* Nginx日志目录：/home/wwwlogs/
* /root/vhost.sh添加的虚拟主机配置文件所在目录：/usr/local/nginx/conf/vhost/
* PureFtpd 目录：/usr/local/pureftpd/
* PureFtpd web管理目录：1.0版为 /home/wwwroot/default/ftp/
* Proftpd 目录：/usr/local/proftpd/
* Redis 目录：/usr/local/redis/

### LNMP相关配置文件位置
* Nginx主配置(默认虚拟主机)文件：/usr/local/nginx/conf/nginx.conf
* 添加的虚拟主机配置文件：/usr/local/nginx/conf/vhost/域名.conf
* MySQL配置文件：/etc/my.cnf
* PHP配置文件：/usr/local/php/etc/php.ini
* php-fpm配置文件：/usr/local/php/etc/php-fpm.conf
* PureFtpd配置文件：/usr/local/pureftpd/pure-ftpd.conf 1.3及更高版本：/usr/local/pureftpd/etc/pure-ftpd.conf
* PureFtpd MySQL配置文件：/usr/local/pureftpd/pureftpd-mysql.conf
* Proftpd配置文件：/usr/local/proftpd/etc/proftpd.conf 1.2及之前版本为/usr/local/proftpd/proftpd.conf
* Proftpd 用户配置文件：/usr/local/proftpd/etc/vhost/用户名.conf
* Redis 配置文件：/usr/local/redis/etc/redis.conf
