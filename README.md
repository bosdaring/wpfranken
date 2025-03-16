# wpfranken
WPFranken is high performance WordPress on Caddy+FrankenPHP

Our official docker image
https://hub.docker.com/r/bosdaring/wpfranken

== installation ==
create a stack with MySQL or remote db \

example.env

WORDPRESS_DB_USER=dbuser
WORDPRESS_DB_HOST=mysql
WORDPRESS_TABLE_PREFIX=wp_
WORDPRESS_DB_NAME=dbname
WORDPRESS_DEBUG=false
WORDPRESS_DB_PASSWORD=changeme*
#listen to HTTP :80 or HTTPS :443
SERVER_NAME=:80

mount volume
/var/www/html/wp-content

happy blogging :)
