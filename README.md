
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
composer install      
php artisan migrate   

http://api.thrivee.test/api/v2/depression/test        
php -S localhost:8000 -t public/       



#### mysql
mysql -u root -p

show databases;   
use thriveedbdev;   
show tables;  
select * from TABLE;   

source /home/vagrant/code/share/thriveedbdev.sql;  


ALTER USER 'root'@'localhost' IDENTIFIED BY 'admin';

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'admin';   

INSERT INTO thriveedbdev.teleconference_transcribe_test (       
  account_id,    
  session_id,    
  speaking_at,    
  transcription,    
  filename   
  )
  
VALUES(   
  337,   
  2,    
  1559732043,   
  "test",   
  "test"   
  );   

DELETE FROM teleconference_transcribe_test WHERE session_id=2;

UPDATE teleconference_transcribe_test SET account_id = 326;

#### frontend
cd thriveethemeupdate  
cp .env.example .env    
edit .env and change the values to your local dev    
npm install   
npm install --global pm2   
npx pm2  

##### vagrant
cat \etc\hosts

vagrant reload --provision    


192.168.10.10   platform.thrivee.test    
192.168.10.10   api.thrivee.test    






