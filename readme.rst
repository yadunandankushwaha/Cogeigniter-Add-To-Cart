###################
Add to Cart codeIgniter-Ajax
###################

Clone the project

*******************
Creating of database structures
*******************

Please create a database, here I create a database with named cart_db.
After that, Insert some data to product table.

*******************
Configuration Codeigniter
*******************

Autoload.php

To configure the autoload.php, please open the folder:

application/config/autoload.php

$autoload['libraries'] = array('database', 'cart');

$autoload['helper'] = array('url');

To configure the config.php, please open the folder:
application/config/config.php

$config['base_url'] = 'http://localhost/cart';

To configure the database.php, please open the folder:
application/config/database.php
And change your database setting.


************
Run the project
************

http://localhost/cart/index.php/product
OR
http://localhost/cart/product
