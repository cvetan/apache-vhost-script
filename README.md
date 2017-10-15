# apache-vhost-script
Simple bash script to create or local vhost on Apache on Debian based systems.

This script (for now) presummes default apache settings, in terms of document root locations, ownership on files, and privileges.

Document root: **/var/www/html**

Owner: **www-data:www-data**

Privileges: **775**

It will create and enable .dev vhost. 
