(.htaccess) :-

php_value upload_max_filesize 128M
php_value post_max_size 128M
php_value max_execution_time 300
php_value max_input_vars 3000
php_value mamory_limit 256M

<IfModule Litespeed>
SetEnv noabort 1
SetEnv noconntimeout 1
</IfModule>

--------------------------------------------------------
(pHp.ini) :-

set_time_limit(1500);
