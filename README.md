# parliament
Настройте веб-сервер

Для OpenServer: поместите проект в папку domains

Для XAMPP: поместите в htdocs

Для WAMP: поместите в www

Создайте базу данных

Откройте phpMyAdmin

Создайте новую базу данных: youth_parliament

Импортируйте файл database.sql

Настройте подключение к БД

Откройте файл config.php

Укажите параметры подключения:

php
define('DB_HOST', 'localhost');
define('DB_USER', 'root');
define('DB_PASS', '');
define('DB_NAME', 'youth_parliament');
Запустите проект

Откройте браузер

Перейдите по адресу: http://localhost/parlament/
