# This script automatically set up a new *Debian* server (IMPORTANT : Debian!), by doing these actions :
#
# * Modification of the root password
# * Adding .email & .forward with the official root email
# * Sending an email to check sendmail
# * Define an hostname for the server
# * Creating users
# * Securing SSH
# * Update the system
# * Install unattended-upgrades
# * Install Fail2Ban
# * Install and set some security for :
# ** Apache
# *** Disable modules : userdir suexec cgi cgid dav include autoindex authn_file status env headers proxy proxy_balancer proxy_http headers
# *** Enable modules : expires rewrite setenvif ssl
# ** Mysql
# *** Execute mysql_secure_installation script
# ** PHP
# *** With modules : cli mysql curl gd mcrypt memcache memcached suhosin
# ** PHPMyAdmin
# ** ProFTPd with MySQL support
#
