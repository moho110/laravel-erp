# laravel-erp
部署

克隆代码：

git clone https://github.com/moho110/laravel-erp.git

安装依赖：

$ composer install

编辑配置：

$ cp .env.example .env

...
DB_DATABASE=database
DB_USERNAME=username
DB_PASSWORD=password
...

生成 KEY：

$ php artisan key:generate  

迁移数据：

php artisan migrate:refresh --seed

本地测试：

$ php artisan serve

安装完成：http://127.0.0.1:8000

    有些朋友对部署表示有压力，但这和一般的 Laravel 应用是没有区别的，线上环境可以参考：https://github.com/summerblue/laravel-ubuntu-init

感谢

后台框架：laravel-admin
