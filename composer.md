参考教程：http://docs.phpcomposer.com/

全局安装：
你可以将此文件放在任何地方。如果你把它放在系统的 PATH 目录中，你就能在全局访问它。 在类Unix系统中，你甚至#可以在使用时不加 php 前缀。

安装Composer:
```
$ curl -sS https://getcomposer.org/installer | php
```
移动composer.phar 到/usr/local/bin/composer
```
$ mv composer.phar /usr/local/bin/composer
```
查看composer的常用命令
```
$ composer
```
使用composer命令的时候需要注意不能用root 用户来执行