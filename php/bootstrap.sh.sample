#!/usr/bin/env bash

echo "Moving into project..."
cd /var/www/sf/

echo "Installing dependencies..."
composer install --prefer-dist --no-interaction

echo "Installing assets..."
./bin/console assets:install
./bin/console assetic:dump

echo "Clearing cache..."
./bin/console cache:clear

echo "Starting server..."
/usr/local/bin/apache2-foreground
