# Laravel Admin 通用后台系统

#### LaravelAdmin v2.0.0版本，将基于laravel优雅风格的特性，以及服务设计模式，重构中，敬请期待。

[LaravelAdmin](https://github.com/yuxingfei/LaravelAdmin) 是基于laravel 7.*的版本和AdminLTE前端样式框架开发的一套通用后台管理系统[LaravelAdmin](https://github.com/yuxingfei/LaravelAdmin)。里面吸取了很多开源项目的精髓,laravel 7、AdminLte、mews/captcha等,开箱即用，非常灵活，该版本是v1.0.0版本，后面根据大家的需求，结合laravel 7的特性，推出更有laravel 7特色的版本。欢迎各位同仁使用后，提出宝贵的意见。欢迎加入laravel admin通用后台系统技术交流QQ群: **682096728**

## LaravelAdmin安装
#### clone 项目到本地
```
GitHub:   git clone git@github.com:yuxingfei/LaravelAdmin.git
```
或
```
码云:   git clone git@gitee.com:yuxingfei/LaravelAdmin.git
```

#### 安装项目依赖
```
composer install
```

#### 配置数据库
```
更改 `.env` 文件内的数据库配置选项,数据库编码推荐`utf8mb4`。
```

#### 运行数据库迁移
```
php artisan migrate
``` 
#### 菜单生成数据填充
```
php artisan db:seed
``` 
#### 公共磁盘创建
```
php artisan storage:link
``` 

#### 最后一步，别忘了把项目设置为程序运行用户哟
```
例如我的程序运行用户是www用户:  chown -R www:www ./LaravelAdmin/
``` 

#### 服务器配置
可参考[Laravel 7 安装配置](https://learnku.com/docs/laravel/7.x/installation/7447)

#### 访问后台
访问`/admin`，默认超级管理员的账号密码都为`super_admin`。


## 补充
本项目采用大量的开源代码，包括Laravel7，AdminLTE、mews/captcha等。
值得注意的是这是Laravel 版本的 通用后台管理系统[LaravelAdmin](https://github.com/yuxingfei/LaravelAdmin),如果大家需要thinkphp版本的后台管理系统，可以使用[BearAdmin](https://github.com/yupoxiong/BearAdmin)。

交流QQ群：[682096728](https://jq.qq.com/?_wv=1027&k=8SMveoJ0)

![Image](https://raw.githubusercontent.com/yuxingfei/images/master/qq_share_code.png)

#### [LaravelAdmin](https://github.com/yuxingfei/LaravelAdmin)效果图

![Image](https://raw.githubusercontent.com/yuxingfei/images/master/home.png)

![Image](https://raw.githubusercontent.com/yuxingfei/images/master/skin_setting.png)

![Image](https://raw.githubusercontent.com/yuxingfei/images/master/user.png)

![Image](https://raw.githubusercontent.com/yuxingfei/images/master/menu.png)

![Image](https://raw.githubusercontent.com/yuxingfei/images/master/role.png)

![Image](https://raw.githubusercontent.com/yuxingfei/images/master/setting.png)

![Image](https://raw.githubusercontent.com/yuxingfei/images/master/database.png)