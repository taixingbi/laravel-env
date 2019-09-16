
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
composer install      
php -S localhost:8000 -t public/       


#### valet
valet install

ping foobar.test

valet install

#### mysql
mysql -u root -p

show databases;   
use DATBASE;   
describe TABLE;  
select * from TABLE;   

ALTER USER 'root'@'localhost' IDENTIFIED BY 'admin';

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'admin';   

source /Users/taixingbi/Desktop/thriveedbdev;


#### laravel
composer global require laravel/installer





#### 
curl -sS https://getcomposer.org/installer | php
