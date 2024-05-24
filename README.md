composer require apiiphim/apii-core -w

php artisan apiionline:install

use ApiiOnline\Core\Models\User as ApiiOnlineUser;

php artisan apiionline:user

Xóa trong routes/web.php
    Route::get('/', function () {
      return view('welcome');
    });
 php artisan optimize:clear
