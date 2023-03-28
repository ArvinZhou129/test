RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://ArvinZhou.github.io/test/index.html$1 [R,L]
