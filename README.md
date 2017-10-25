### 这个是基于dockerhub的官方php的修改版本

生成了一个debug的版本

* php安装路径：/usr/local/php
* 配置文件路径：/usr/local/php/lib/

### 运行方式

* 先安装docker
* git clone https://github.com/yuyongpeng/docker-php.git
* cd docker-php/alpine
* docker build -t php:alpine .
* docker run -d php:alipine
* docker exec -ti xxxxxxxx bash

### 配置文件
* php.ini路径：/usr/local/etc/php/php.ini，需要上传
* php.conf:  /usr/local/etc/php/conf.d
* /usr/local/etc/php-fpm.conf
* /usr/local/bin/php
* /usr/local/bin/php-config
* /usr/local/bin/phpize
* /usr/local/sbin/php-fpm
* /usr/local/bin/pecl