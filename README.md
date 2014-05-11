drupalDays2014 (Symfony talk)
==============

Slide e Progetto Symfony per l'evento Drupal Days 2014 

Per l'installazione del progetto, posizionarsi nella root con il terminale ed installare composer

`cd drupalDays2014/talksymfony`

`curl -sS https://getcomposer.org/installer | php`

`php composer.phar update`

`php app/console doctrine:database:create`

`php app/console doctrine:schema:update --force`
