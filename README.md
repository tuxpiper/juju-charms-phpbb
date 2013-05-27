juju charm for phpBB

Depends on mysql charm for database.

In order to deploy, clone this git repo inside folder "raring" of your local juju charms repository and

juju deploy mysql mysql-phpbb 
juju deploy --repository=<path to repo> local:raring/phpbb phpbb
juju add-relation phpbb mysql-phpbb

This has been tested only with the Ubuntu raring series

