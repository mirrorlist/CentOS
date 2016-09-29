# CentOS repo mirror

## Usage

Add `/etc/yum.repos.d/mirror.repo`

```ini
[mirror]
gpgcheck=0
name = Red Hat Linux $releasever - $basearch - mirror
baseurl=https://mirrorlist.github.io/centos/6.8/
```

**Clean cache**

```
yum clean all
yum repolist all
```

**Install httpd**

```
yum install httpd
```

**Install mysql 5.6**

```
yum install mysql-server

service mysqld start
chkconfig mysqld on

mysql_secure_installation
```

**Install php 5.6**

```
yum install php php-bcmath php-channel-nrk php-cli php-common php-devel php-fpm php-gd php-gmp php-mbstring php-mcrypt php-mysqlnd php-nrk-Predis php-pdo php-pear php-pecl-igbinary php-pecl-jsonc php-pecl-jsonc-devel php-pecl-redis php-pecl-xdebug php-pecl-zip php-php-gettext php-phpseclib php-process php-recode php-symfony-class-loader php-symfony-common php-tcpdf php-tcpdf-dejavu-sans-fonts php-tidy php-xml phpmyadmin
```

**Install redis**

```
yum install redis
```

**Install erlang**

```
yum install erlang
```

**Install rabbitmq**

```
yum install rabbitmq-server
yum install librabbitmq librabbitmq-last librabbitmq-last-tools librabbitmq-last-devel
```

**Install amqp php plugin**

```
yum install php-pecl-amqp
```

**Install monit**

```
yum install monit
```

**Instanll python27**

```
yum install centos-release-SCL
yum install python27
```
