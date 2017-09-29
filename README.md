# mysql-cron
Mysql docker image with cron added

This is for periodically backing up a database that's running in another container.  This backup can be done via cron and it's resource usage can be limited.

Mount the following directory & place the cron job files there & set their perms to 644: /etc/cron.d
