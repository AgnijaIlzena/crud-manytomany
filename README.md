# crud-manytomany

composer install

--data base
symfony console doctrine:database:create
--migrations
symfony console make:migration
symfony console doctrine:migration:migrate
symfony console d:s:u --force
