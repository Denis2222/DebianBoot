# DebianBoot

cd /etc/apt/
vim sources.list

apt-get update

apt-get upgrade

apt-get install linux-headers-$(uname -r)

mv composer.phar /usr/local/bin/composer

aptitude install vim git tig terminator curl sshfs chromium gcc

apt-get install apache2 apache2-doc apache2-utils libapache2-mod-ruby libapache2-mod-perl2 libapache2-mod-python python-mysqldb libapache2-mod-php5 php5 php-pear php5-xcache php5-mysql phpmyadmin mysql-server phpmyadmin php5-intl php5-curl php5-xsl

vim /etc/apache2/apache2.conf 
vim /etc/apache2/envvars

a2enmod rewrite

apt-get install nodejs nodejs-legacy npm

npm install -g grunt grunt-cli bower

wget http://c758482.r82.cf2.rackcdn.com/sublime-text_build-3065_amd64.deb
sudo dpkg -i sublime-text_build-3065_amd64.deb
