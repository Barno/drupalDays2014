drupalDays2014 (Symfony talk)
==============

The sample code used for the Introductory Symfony talk held by Alessio Barnini during the Drupal Days 2014 on 8th May in Milan

## Usage
First of all, clone the repo:

```bash
$ git clone https://github.com/Barno/drupalDays2014/
```

```bash
$ cd drupalDays2014/talksymfony
$ curl -sS https://getcomposer.org/installer | php
$ php composer.phar update
$ php app/console doctrine:database:create
$ php app/console doctrine:schema:update --force

```
