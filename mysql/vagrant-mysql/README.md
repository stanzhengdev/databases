- copy this vagrant file
- delete the vagrant cache, (.vagrant)
- vagrant up
- add my.cnf
- sudo apt -get install mysql-server
- sudo cp /vagrant/my.cnf /etc/mysql/my.cnf
- sudo service mysql restart
- mysql 


create user 'admin'@'10.0.2.2' identified by 'admin';
grant all on testing.* to 'admin'@'%' identified by 'admin';
flush privileges;


