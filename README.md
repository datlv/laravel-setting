# Laravel Setting

Quản lý cấu hình

## Install

* Thêm vào file composer.json của app
```json
	"repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/datlv/laravel-setting"
        }
    ],
    "require": {
        "datlv/laravel-setting": "dev-master"
    }
```
``` bash
$ composer update
```

* Thêm vào file config/app.php => 'providers'
```php
	Datlv\Setting\ServiceProvider::class,
```

* Publish config và views
``` bash
$ php artisan vendor:publish
```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
