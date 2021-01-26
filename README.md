# 构建 PHP 项目

## PHP 官网

[https://www.php.net](https://www.php.net)

## PHP 运行环境

尽量选择 PHP 最新稳定版。特殊场景下根据需求选择。

## 选择 PHP 编辑器

好的编辑器，需要：代码高亮，自动补全，函数跳转，反应迅速。

* PhpStorm

## 选择 PHP 开发框架

选择好一款框架后，便基本确定了开发模式，说白了就是在框架既定的模式下进行开发工作。

### 传统老牌框架

传统型框架，无非做了一件事，接收来自用户代理（用户代理是指 User Agent，一般指浏览器）的请求并将其转化为响应返回。再深一步讲，定义了一套 HTTP 请求的生命周期，有时为了扩展性要求则添加了勾子或事件。围绕这一中心，额外添加一些常用功能组件等。常用功能组件有：日志记录，国际化，多应用入口，模块化，视图，数据库迁移，ORM/AR，过滤器，验证器，认证，授权，图片验证码，Session，Cookie 等。

所谓传统，更重要的是只能在 php-fpm 模式下运行，性能一般不理想。

* Yii2
* ThinkPHP
* Symfony
* Laravel
* CakePHP
* CI

### 现代化 PHP 开发框架

讲到现代化，最重要的一点是摆脱原来 php-fpm 的运行模式，转而变为常驻内存的方式，或是采用协程，或是多进程等。这里指 swoole 一类，还有就是 workerman 及 reactphp 一类。

采用现代化框架，首中之重是建立写的编程思想，略微加重了思想负担。举个例子，不能随便使用 `exit` 函数。

* Hyperf
* IMI
* Swoft
* easyswoole
* mixphp
* WorkerMan

## 选择 PHP 应用系统

### 内容管理系统

* joomla cms
* octobercms
* [getgrav/grav](https://github.com/getgrav/grav) | Modern, Crazy Fast, Ridiculously Easy and Amazingly Powerful Flat-File CMS
* DEDE

### 电商系统

* opencart
* megento
* fecmall

### 未归类

* [monicahq/monica](https://github.com/monicahq/monica) | Personal CRM. Remember everything about your friends, family and business relationships.

## PHP 库

* [guzzle](https://github.com/guzzle/guzzle) | Guzzle, an extensible PHP HTTP client
* phpoffice/spreadsheet
* [phpseclib](https://github.com/phpseclib/phpseclib) | PHP Secure Communications Library
* [uuid](https://github.com/ramsey/uuid) | A PHP library for generating universally unique identifiers (UUIDs).
* [hashids](https://github.com/vinkla/hashids) | A small PHP library to generate YouTube-like ids from numbers. Use it when you don't want to expose your database ids to the user.
* [whoops](https://github.com/filp/whoops) | PHP errors for cool kids
