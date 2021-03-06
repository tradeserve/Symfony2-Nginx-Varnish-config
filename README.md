Symfony2 under Nginx (PHP5-FPM) & Varnish config
===============================================

About
-----

This is a default configuraion example of Symfony2 application being hosted via Nginx server. 
Varnish is being used as a reverse proxy accellerator. 

Hosted under Debian/Ubuntu server.

Repository folders mimic default Debian catalogue structure.

Installation
------------

See: [INSTALL.md](https://github.com/egils/Symfony2-Nginx-Varnish-config/blob/master/INSTALL.md).

Testing environment - Hardware
------------------------------

* Intel i7-3770K @ 4.3 GHz
* Memmory: 7.7Gb @ 1866 MHz
* HDD: 100Gb ssd - Intel 520 series

Testing environment - Software
------------------------------

* OS: Linux mint 17 (Ubuntu 14.04)
* Nginx: 1.4.6
* Symfony: 2.5.4
* PHP: 5.5.9

Credit
------

* Ubuntu and Debian - Nginx Configuration: http://www.rackspace.com/knowledge_center/article/ubuntu-and-debian-nginx-configuration
* Configuring a web server: http://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html
* How to use Varnish to speed up my Website: http://symfony.com/doc/current/cookbook/cache/varnish.html
* How GZIP, and GZIP+ESI works in Varnish: https://www.varnish-cache.org/docs/3.0/phk/gzip.html#phk-gzip
