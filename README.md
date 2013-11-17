browscap4j
==========

Tools for working with the browscap.com browser capability list

Browscap is a database of browser user agent strings and associated browser capabilities used heavily by PHP and Drupal.

This project provides a wrapper around the the browscap.ini files (available at [http://tempdownloads.browserscap.com/](http://tempdownloads.browserscap.com/).

This project is in some parts inspired by [java-browscap](https://github.com/rafeco/java-browscap) but intends to add a few additional features include:
 - Flexible loading from classpath, filesyste, web
 - Caching of retrieved user agents for improved performance
 - Playing nicely with web-hosted .ini files to reduce bandwith and update only as needed.


