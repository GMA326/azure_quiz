# azure_quiz
sudo apt install update
sudo apt install nginx
if you use port 80 go into /etc/nginx/sites-available/ 
sudo nano default and change ports from 80 to 8080 or 8090 in listen 
change in default servername to domain
sudo nginx -t to control syntax line
sudo systemctl restart nginx
sudo ufw allow 8090/tcp
sudo systemctl status nginx.service
copy all 4 files into var/www/html 
should work now enjoy!

using a simple nginx webserver 
https://gaetanomanduca.tech

Azure_Quiz with github and linkedin footer thx https://github.com/korny861 for your collaboration!
