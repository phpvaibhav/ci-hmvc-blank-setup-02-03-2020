# NEW HMVC SETUP 02-03-2020
# RewriteEngine on
# RewriteCond $1 !^(index\.php|resources|robots\.txt)
# RewriteCond %{REQUEST_FILENAME} !-f
# RewriteCond %{REQUEST_FILENAME} !-d
# RewriteRule ^(.*)$ index.php/$1 [L,QSA] 

# RewriteRule .* - [E=CI_ENV:testing]
