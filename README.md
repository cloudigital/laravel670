# laravel_v690
Laravel v6.9.0

#upgrade php
https://linuxconfig.org/how-to-install-or-upgrade-to-php-7-on-centos-linux-server

wget -q http://rpms.remirepo.net/enterprise/remi-release-7.rpm
wget -q https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm

# rpm -i remi-release-7.rpm epel-release-latest-7.noarch.rpm
FOR PHP 7.0 EXECUTE:
# yum-config-manager --enable remi-php70
FOR PHP 7.1 EXECUTE:
# yum-config-manager --enable remi-php71
FOR PHP 7.2 EXECUTE:
# yum-config-manager --enable remi-php72

yum install php
OR
# yum update


yum search php-xml
yum install php74-php-xml.x86_64
yum install php-bcmath
