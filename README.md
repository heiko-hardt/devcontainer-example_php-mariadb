# devcontainer-example_php-mariadb

Example devcontainer setup for PHP & MariaDB using the default template

Template Source: https://github.com/devcontainers/templates/tree/main/src/php-mariadb

## Verify the container:
```
# Add a simple PHP file to the Apache document root
$ echo "<?php phpinfo();" > /var/www/html/index.php

# Start the Apache server
$ apache2ctl start

# Port forwarding on port 8080 should now be active
# Open http://localhost:8080/ to view the PHP info page
```
