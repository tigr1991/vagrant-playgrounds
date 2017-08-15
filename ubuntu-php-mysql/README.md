# Создание БД в MySQL
1. ```sudo mysql```
2.  В командной строке MySQL введите команду ```CREATE DATABASE <DATABASENAME>;```. Замените `<DATABASENAME>` названием вашей базы данных. Оно не может содержать пробелы.
3. Отобразите список доступных баз данных. Введите команду ```SHOW DATABASES;```

И др. http://ru.wikihow.com/%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D1%82%D1%8C-%D0%B1%D0%B0%D0%B7%D1%83-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%D0%B2-MySQL

sudo mysql -e "create user 'root'@'%' identified by ''; grant all privileges on *.* to 'root'@'%' with grant option; flush privileges;"