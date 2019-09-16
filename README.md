
lsof -n -i:80 | grep LISTEN
sudo pkill nginx   

#### brew
brew install php   
brew install mysql    
brew services list      

#### composer 
brew install composer     

export PATH="$PATH:$HOME/.composer/vendor/bin"     
echo 'export PATH="$PATH:$HOME/.composer/vendor/bin"' >> ~/.bashrc      
composer global require laravel/valet       

##### download composer.phar
https://getcomposer.org/composer.phar


#### run project
php artisan migrate
php -S localhost:8000 -t public/


#### valet
valet install

ping foobar.test

valet install


mysql -u root -p

show databases;
use DATBASE;
describe TABLE;
select * from TABLE;

#### laravel
composer global require laravel/installer



ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'admin';

source /Users/taixingbi/Desktop/hunter.sql;

#### 
curl -sS https://getcomposer.org/installer | php
