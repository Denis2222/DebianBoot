# DebianBoot

cd /etc/apt/

vim sources.list

apt-get update

apt-get upgrade

aptitude install vim git tig terminator curl sshfs chromium gcc apache2 apache2-doc apache2-utils libapache2-mod-ruby libapache2-mod-perl2 libapache2-mod-python python-mysqldb libapache2-mod-php5 php5 php-pear php5-xcache php5-mysql phpmyadmin mysql-server phpmyadmin php5-intl php5-curl php5-xsl linux-headers-$(uname -r) nodejs nodejs-legacy npm

npm install -g grunt grunt-cli bower

curl -sS https://getcomposer.org/installer | php

mv composer.phar /usr/local/bin/composer

vim /etc/apache2/apache2.conf

vim /etc/apache2/envvars

a2enmod rewrite

wget http://c758482.r82.cf2.rackcdn.com/sublime-text_build-3065_amd64.deb
dpkg -i sublime-text_build-3065_amd64.deb
