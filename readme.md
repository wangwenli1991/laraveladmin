LaravelAdmin

一个完整的laravel dashbord模板与laravel 5.3 + gentelella管理模板

LaravelAdmin是一个管理面板，配有Laravel 5.3和gentelella管理模板。

管理面板与Laravel 5.3管理用户认证，注册电子邮件确认，密码恢复，api管理。Gentelella管理模板有一个管理功能的日志。我们将覆盖所有这些+全面的用户身份验证与社会登录，文章rwiting和api。我们继续工作

一个Laravel 5.3.x项目。

Laravel管理面板功能
建在Laravel 5.3上
使用MySQL数据库
依赖关系由COMPOSER和Bower进行管理
Laravel脚手架用户和管理员身份验证。
快速安装

克隆项目 sudo git clone https://github.com/mshossain110/LaravelAdmin.git

为项目创建一个MySQL数据库

创建或复制.env文件运行 cp .env.example .env

配置.env文件

sudo composer update从项目根文件夹运行

给予完整的文件许可 sudo chmod -R 755 LaravelAdmin

生成密钥 php artisan key:generate

创造laravel桌 php artisan migrate

运行服务器 php artisan serve

浏览浏览器 http://localhost:8000

*要访问您需要用户帐户。