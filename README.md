YuidoAdmin
===========

A Symfony2 model project intended to be a starting point for backend web application development
with sonataAdmin and FOSUser.

Instalation
-----------

    git clone https://github.com/inaki76/YuidoAdmin.git

    cd Yuido

    php composer.phar install

    php app/console doctrine:database:create

    php app/console doctrine:schema:create

    php app/console jwsecurity:fixtures:load 

Point your browser to http://your.server/app_dev.php and enter with username 'admin' and password 'changeme'

