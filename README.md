Symfony twig
============

Simple Project to build web application with Symfony, using Twig engine for html template.

What's inside?
--------------

Current using these resources:

  * Bootstrap 3

  * Sb-admin-2 opensource for dashboard

  * Twig as template engine;

  * Doctrine ORM/DBAL;

  * Swiftmailer;

Get started
-----------

Install all dependencies

```
composer install

bower install
```

Download sb-amin-2 from [https://github.com/BlackrockDigital/startbootstrap-sb-admin-2/archive/gh-pages.zip](https://github.com/BlackrockDigital/startbootstrap-sb-admin-2/archive/gh-pages.zip).
Put to lib/ then extract.

Run shell to update links to dependencies

```
cd web/assets
./start.sh
```

Run server test

```
php app/console server:run localhost:8888
```

Point browser to localhost:8888 for homepage, or localhost:8888/admin for admin dashboard.

Enjoy!
------