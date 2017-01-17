# php 个人编程规范
## 参考
> https://segmentfault.com/a/1190000000443795
> https://github.com/laravel

## 项目名称
第一个字母大写，驼峰，名词
### 例子
> PHPMailer
> SecureHeaders

## 模块文件夹
第一个字母大写， 名词
### 例子
> Http
> Exceptions
> Providers
> Controllers

## 文件名
第一个字母大写, 驼峰, 名词/ 动词+名词
### 例子
```php
AuthServiceProvider.php
Kernel.php
EncryptCookies.php
```

## 常量
全部大写，下划线分割
### 例子
> DEFAULT_SMTP_PORT
> MAX_LINE_LENGTH

## 函数名
第一个字母小写, 驼峰, 动词+名词
### 例子
```php
  function getUserName()
```
