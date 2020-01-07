###################
Add to Cart codeIgniter-Ajax
###################

Clone the project

*******************
Creating of database structures
*******************

Please create a database, here I create a database with named cart_db. <br>
After that, Insert some data to product table.

**************************
Changelog and New Features
**************************

You can find a list of all changes for each release in the `user
guide change log <https://github.com/bcit-ci/CodeIgniter/blob/develop/user_guide_src/source/changelog.rst>`_.

*******************
Configuration Codeigniter
*******************

Autoload.php

To configure the autoload.php, please open the folder:<br>
application/config/autoload.php <br><br>

$autoload['libraries'] = array('database', 'cart');<br>
$autoload['helper'] = array('url');<br><br>

To configure the config.php, please open the folder:<br>
application/config/config.php<br>

$config['base_url'] = 'http://localhost/cart';<br><br>

To configure the database.php, please open the folder:<br>
application/config/database.php<br>
And change your database setting.


************
Run the project
************

http://localhost/cart/index.php/product<br>
OR<br>
http://localhost/cart/product