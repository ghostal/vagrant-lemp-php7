# vagrant-lemp-php7
A simple Vagrant development box with PHP 7 and phpmyadmin

* ubuntu/trusty64
* nginx
* MariaDB 10.1
* PHP 7
* composer
* phpMyAdmin (`STABLE` branch)

## Instructions
Simply `vagrant up` from your terminal:
```
$ vagrant up
```
Navigate to the following URLs to use:
* Your Site: http://192.168.33.10/
* phpMyAdmin: http://192.168.33.10/phpmyadmin/

The MariaDB server has a blank root password. For ease of use, the login details are stored in the phpMyAdmin config at `/usr/share/phpmyadmin/config.inc.php`. If you wish to change the MariaDB root password, you will need to amend this config.
