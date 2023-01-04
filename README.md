# Laravel SSH WEB Client
Laravel SSH WEB Client that use Laravel and websockets to connect to a SSH server by webclient. You can store the server and the credentials in the app.
It includes a simple way to SSH into remote servers and run commands, allowing you to easily build Artisan tasks that work on remote servers.
## Installations Steps
- You need to have libssh2 installed in your server and host the project on a linux server and enable ssh extension -> https://pecl.php.net/package/ssh2
- composer install
- npm install
- php artisan migrate
- cd `ssh-server` > `composer install`
- From Root: `php ssh-server/bin/websocket.php` 