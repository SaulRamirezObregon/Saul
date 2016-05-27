composer install
vendor/bin/doctrine orm:schema-tool:create
vendor/bin/doctrine orm:schema-tool:update --force
vendor/bin/doctrine orm:schema-tool:update --force --dump-sql

php create_product.php NombreProductoAInsertar NombreCategoriaProducto
php create_user.php NombreUsuarioAInsertar
php update_product.php IdProduct NombreAactualizar
php create_bug.php NombreBug
php list_products.php
php show_product.php IdProducto



