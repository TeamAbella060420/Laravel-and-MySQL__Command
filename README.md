# Laravel-and-MySQL__Command
 
Create Laravel Project

1. laravel new project-name
2. cd project-name
3. php artisan serve
4. Create a database from php admin mysql
5. Go to .env, refactor the DB code, replace code to DB_HOST=localhost 
DB_DATABASE=laravel_ajax `This is the name of the data base in the my SQL`
6. php artisan make:model Employee -m `Create a model and migration`
7. php artisan make:controller EmployeeController `Create a controller`

database command
1. mysql -u root -p
2. Enter password
3. use 789_2nd_db1;
4. show tables;
5. select * from url;
6. update url set name = "link1" where id = 1;

database deployment
1. mysql -u root -p
2. Enter password
3. use 789_2nd_db1;
4. source /tmp/database.sql

msql command 
1. go to xampp shell
2. mysql -u root -p
3. Enter password
4. show databases 
5. use fullstack
6. show tables
7. \q
8. mysqldump -u root -p full_stack>newdatabase.sql
9. Enter password
10. create database test;
11. use test
12. show tables;
13. source newdatabase.sql
14. show tables
15. show databases