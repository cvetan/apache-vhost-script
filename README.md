# apache-vhost-script
Simple bash script to create or delete, local vhost on Apache web server on Debian based systems.

This script (for now) presummes default apache settings, in terms of document root locations, ownership on files, and privileges.

Document root: **/var/www/html**

Owner: **www-data:www-data**

Privileges: **775**

It will create and enable .dev vhost.

Clone script into **/usr/local/bin** for global access system wide.
It will need root privileges.
