# web-php-apache2-simple
A hello world PHP script

# Recipe

FROM codenvy/php

# Commands to run

Command #1 Start Apache

sudo service apache2 start

Command #2 Stop Apache

sudo service apache2 stop

Command #3 Follow access and error logs

sudo tail -f /var/log/apache2/access.log -f /var/log/apache2/error.log

