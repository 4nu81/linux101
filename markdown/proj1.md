### Hands On 

#### Apache website, shared access for contributors.

* Install Apache with apt-get
* Set the DocumentRoot in /etc/apache2/sites-available to /var/www/mysite
* Get the code: https://github.com/BlackrockDigital/startbootstrap-modern-business/archive/master.zip 
* Unzip the code under /var/www and rename to "mysite"
* Change the owner to the apache user "www-data"
* Test at http://yourhost
* Create a group "webdev" and set grant read, write, and SGID permissions recursively on "mysite"
* Add users to the group
* Let both users add, modify, delete files and test. Check for permission errors.

