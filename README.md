```
<VirtualHost *:80>
DocumentRoot "D:/xampp/htdocs/samitivejwebsite"
ServerName samitivejhospitals.dev
ServerAlias www.samitivejhospitals.dev
<Directory "D:/xampp/htdocs/samitivejwebsite">
Order allow,deny
Allow from all
</Directory>
</VirtualHost>
```
