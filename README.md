# Panel-SSH
Panel para control de usuarios SSH

sudo pecl channel-update pecl.php.net
sudo apt-get install libssh2-1-dev
sudo pecl install -a ssh2-0.12
echo extension=ssh2.so /www/server/php/54/etc/php.ini
