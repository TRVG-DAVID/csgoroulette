Comandos WiseR97:
apt-get update
apt-get install apache2
apt-get install mysql-server
apt-get install php5-mysql php5-curl php5-gd php5-intl php-pear php5-imagick php5-imap php5-mcrypt php5-memcache php5-ming php5-ps php5-pspell php5-recode php5-snmp php5-sqlite php5-tidy php5-xmlrpc php5-xsl
apt-get install phpmyadmin
 
in apache2.conf write:
Include /etc/phpmyadmin/apache.conf
 
sudo a2enmod rewrite
sudo service apache2 restart
sudo nano /etc/apache2/sites-available/000-default.conf
 
Code:
<Directory "/var/www/html">
AllowOverride All
</Directory>
    go to /etc/apache2/sites-av and open default
    replace AllowOverride None to AllowOverride All
    /etc/init.d/apache2 restart
    domain.com/phpmyadmin
    make a new db called csgo
    upload the .sql from the script
    - a2enmod rewrite
    --
    - apt-get install curl
    - curl -sL https://deb.nodesource.com/setup_0.12 | bash -
    - apt-get install -y nodejs
    go to putty /home/
    create directory called "bot"
    copy paste all the bot files there (/home/bot)
    prices 777
    cd /home/bot
    -npm install mysql
    -npm install log4js
    -npm install socket.io
    -npm install request
    -npm install fs
    -npm install md5
    -npm install sha256
    -npm install mathjs
    -npm install forever-monitor
    -npm install forever -g
    -npm install steamcommunity
    -npm install steam-totp
    -npm install steam-tradeoffers
    -npm install async
    -npm install engine.io
    --
    open index.php
    change db info
    change steam api key
    open secret.php
    change db info
