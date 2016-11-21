#### Hands On: LAMP stack and app installieren

* install Apache, PHP, PostgreSQL and PHP/Apache deps with Apt
 *  apache2 postgresql libapache2-mod-php5 php5-gd php5-json php5-pgsql php5-curl php5-intl php5-mcrypt php5-imagick

* get the applicateion source at: https://download.owncloud.org/community/owncloud-9.1.2.tar.bz2

* unpack code to the desired webroot, adjust Apache config as necessary

* fix permissions for apache user

* enable Apache mods
 * headers, env, dir, mime

* create a Postgresql user for the application, noting username and password.
* create a database owned by this user

* restart Apache and start the configuration wizard at http://yourhost

#### Advanced:

* Create an Apache Name-Based Virtual Host for your app
* Acquire an Let's-Encrypt SSL Certificate and configure Apache to serve SSL. Use the Certbot package from jessie-backports and set up auto-renewal.


