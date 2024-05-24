composer require apiiphim/apii-core -w

php artisan apiionline:install

use ApiiOnline\Core\Models\User as ApiiOnlineUser

php artisan apiionline:user

location / {
    try_files $uri $uri/ /index.php?$query_string;
  }