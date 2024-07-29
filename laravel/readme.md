## After launching the docker compose

- You can use laravel installer with `/root/.config/composer/vendor/bin/laravel`
- Apache is made to look in var/www/html/public, so do not create your laravel inside a directory, it won't work
- Change the chmod for the storage directory so it is writable
- Remember to change the mysql information in .env, the host is db
- Play the migration with `php artisan migrate`
- It's done, enjoy