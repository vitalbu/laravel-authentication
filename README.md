# Laravel Authentication

***
## Установка
Установка осуществляется с помощью менеджера пакетов Composer

1. Забираем проект
	``` 
    git clone https://github.com/vitalbu/laravel-authentication.git
	``` 

2. Устанавливаем зависимости
	``` 
    composer install
	``` 
		
3. Настраиваем подключение к БД в файле .env (указываете свои настройки)

	```       
	DB_CONNECTION=mysql
	DB_HOST="MariaDB-10.3"
	DB_PORT=3306
	DB_DATABASE=laravel
	DB_USERNAME=root
	DB_PASSWORD=
	```

4. Создаем БД
5. Выполняем миграции БД
	```       
	php artisan migrate
	```
