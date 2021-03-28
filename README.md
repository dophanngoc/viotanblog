#### viotanblog
This is a customized template to downloading from https://bootstrapious.com/. It was modified to handle django framework on my own blog site without commercial purpose.
#### Install requirement packages
```
pip install -r requirements.txt
```
- extract files and folder to web project folder and reload service
```
sudo systemctl stop apache2
cp * /var/www/html
sudo systemctl start apache2
```
- access to localhost ip
```
127.0.0.1
```
