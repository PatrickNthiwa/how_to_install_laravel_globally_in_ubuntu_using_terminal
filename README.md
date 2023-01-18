[# **How to install laravel Globally on Ubuntu/linux**](https://github.com/PatrickNthiwa)

=================================================================================

## Introduction

Laravel uses composer to run and create projects,before proceeding with this install,please ensure you have composer install globally,is not you must first install from their official page [here](https://https://getcomposer.org/doc/00-intro.md).

Composer is a tool for dependency management in PHP. It allows you to declare the libraries your project depends on and it will manage (install/update) them for you.

Open your terminal by using **Ctrl+Alt+T** and type the following commands.

## [ Step 1 : Laravel installation](https://#)

```php
composer global require "laravel/installer"
```

## [Step 2 : Add composer to path .bashrc file to access laravel globally](https://#)

```python
cd ~
sudo nano .bashrc
```

## [Step 2(i): Edit environment config path file and by adding this line](https://#)

```python
export PATH="$PATH:$HOME/.config/composer/vendor/bin"
```
## [Step 2(ii) :Hot Reload config path](https://#)

```python
source ~/.bashrc
```

## [Step 3 : Create a new Laravel application](https://#)

```python
laravel new mail
```
## Step 4 : Install missing composer packages and their dependencies

```python
cd mail
composer install && composer update
```

## [Step 5: Test the application](https://#)

Open the application using your favorite IDE i.e *PHPstorm* or *code*

```python
php artisan serve
```


## [Step 6: Stop server afterwards.](https://#)
 You have successfully installed and tested laravel globally.Well done.
 Terminate **php server** in terminal by pressing =>
  ```python
Ctrl+C
```


**Courtesy**
##### ![PattiePHP](https://#)
