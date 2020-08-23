= Time To Buy
A free app for current and historical foreign exchange rates published by the [European Central Bank](https://exchangeratesapi.io/).

== Running locally
1. Download the project
```
mkdir timetobuy
cd timetobuy
git init
git remote add origin https://github.com/rezehnde/timetobuy.git
git pull origin master
composer update
```
2. Configure the database into .env file and run:
```
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
php bin/console doctrine:fixtures:load
```

Icon by [Icons8](https://icons8.com)