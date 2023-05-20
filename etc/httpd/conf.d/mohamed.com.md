```
<VirtualHost *:80>
ServerName mohamed.com
DocumentRoot /var/www/mohamed.com
DirectoryIndex index.html
</VirtualHost>
<Directory "/var/www/mohamed.com">
AllowOverride All
Require all granted
</Directory>
```
