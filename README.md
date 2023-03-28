RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://ArvinZhou129.github.io/test/index.html$1 [R,L]
