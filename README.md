drupalDays2014 (Symfony talk)
==============

The sample code used for the Introductory Symfony talk held by Alessio Barnini during the Drupal Days 2014 on 8th May in Milan

What's inside
- Form for insert Data
- Validation Form
- Retrieve,Write and Delete Data From DataBase
- Ajax Call for retrieve data


## Usage
First of all, clone the repo:

```bash
$ git clone https://github.com/Barno/drupalDays2014/
```

Then 

```bash
$ cd drupalDays2014/talksymfony
$ curl -sS https://getcomposer.org/installer | php
$ composer install
$ php app/console doctrine:database:create
$ php app/console doctrine:schema:update --force

```
Now you can connect to  

```bash 
http://localhost/path/to/symfony/app/web/config.php
```

If you get any warnings or recommendations, fix them before moving on.

After That

```bash 
http://localhost/path/to/symfony/app_dev.php
```


