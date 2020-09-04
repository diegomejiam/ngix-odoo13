# ngix-odoo13
```
sudo apt-get install nginx
cd /etc/nginx/sites-available
git clone https://github.com/diegomejiam/ngix-odoo13
cd ngix-odoo13/
sudo cp /etc/nginx/sites-available/ngix-odoo13/default.conf /etc/nginx/sites-available/default.conf
cd ..
mv default default-temp
mv default.conf default
nginx -s reload
```
