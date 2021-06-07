# frontend
```
$ sudo apt update
$ sudo apt install nginx -y
$ sudo apt install npm -y
```
$  curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
$  sudo apt-get install -y nodejs
$ sudo su -
# systemctl start nginx
#  cd /var/www/html
# mkdir todo
# cd todo
# git clone https://github.com/zelar-soft-todoapp/frontend.git
# cd frontend/
# npm install
after  node modules folder will be created
# cd /etc/nginx/sites-available
# vim default  
change root path as root /var/www/html/todo/frontend/dist;
Then enter into this path /var/www/html/todo/frontend
# cd /var/www/html/todo/frontend
# npm run build
after building have to start 
#npm start

![image](https://user-images.githubusercontent.com/82602260/116800694-22bcc880-ab21-11eb-9c63-102be14d433d.png)
