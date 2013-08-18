---
layout: post
title: "PHP之道"
author: Yanguang Lan
categories:
- php
- learning
---

<div class="image">
  <img alt="" src="/images/posts/php-the-rightway.jpg" />
  <small>PHP之道</small>
</div>

###军规

通常PHP入门都是从阅读[手册](http://www.php.net/manual/zh/index.php)开始，也有的直接拿个论坛代码改改。
PHP语法简单，约束少。因此网络上充斥着大量不入流的文章或是教程。对于初学者来说甚至有毒害。
为此，[phptherightway](http://www.phptherightway.com/) 一个开发者组织发起的针对初学者的入门指导建议。

一个PHP开发者需要了解和掌握的几个方向点：

####开发环境

初学者建议安装集成环境，然后再此之上运行脚本。例如Mac系统下的MAMP，Window系统下的WAMP、XAMPP、AppServ等。
当然PHP5.4内置了Web服务，可以直接运行PHP脚本。[参考链接](http://www.php.net/manual/en/features.commandline.webserver.php)

多人开发的时候为了统一环境，通常的方式是将开发环境部署在虚拟机里。这样只要使用同一个配置的虚拟机就可以了。
[Vagrant](http://vagrantup.com/) 就是一个很好的管理配置虚拟机的方案。

####编码风格

在写代码之前必须好好了解下编码风格，这是非常重要的。
虽然PHP编码风格没有明文的规则，但目前已经有开发者组织发起
了一些公约。包括[PSR-0](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md) [PSR-1](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md) [PSR-2](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md)

以下有比较成熟的编码风格可以参考
[PEAR Coding Standards](http://pear.php.net/manual/en/standards.php)
[Zend Coding Standards](http://framework.zend.com/wiki/display/ZFDEV2/Coding+Standards)

####依赖管理

PHP和其他语言一样拥有大量的可重用的第三方类库和组件。

[PEAR](http://pear.php.net/) 官方的第三方类库包管理器，PHP安装包里面自带，需要手动安装下。通常用于系统级别的依赖管理。
[Composer](http://getcomposer.org/) 目前很流行的第三方类库包管理器，并且兼容PEAR，通常用于项目级别的依然管理。

####开发实践

1、PHP包括函数编程和面向对象编程。
2、PHP5.3以后包含了很多SPL标准函数库和编程接口。
3、PHP对数据库的操作请使用更高效安全的PDO扩展。
4、PHP开发中通常使用的几种设计模式有：工厂模式、单例模式、策略模式、观察者模式、MVC、HMVC等。
5、处理程序错误和异常。
6、代码安全性考虑。
7、代码单元测试与持续化集成发布。
8、使用缓存提高程序性能。
9、使用框架开发应用程序。
10、使用编辑器提高开发效率。


###接下来

[phptherightway](http://www.phptherightway.com/)

[30+ PHP Best Practices for Beginners](http://net.tutsplus.com/tutorials/php/30-php-best-practices-for-beginners/)

（完）