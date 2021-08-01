<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## <p align="center"> Adaptive Network Laboratory WEB  Migration </p>
# Adaptive Network LAB Laravel-8 AllinOne
Test stagging : [https://lrv8.bignetlab.com]
```
Env:
1. CPanel
2. Domain
3. PHP 7.3
```
# DEPLOY PADA HOSTINGAN (CPANEL):
```
A. PASTIKAN SEBELUM UPLOAD KE HOSTINGAN AGAR MELAKUKAN CLEAR CACHE TERLEBIH DAHULU PADA KOMPUTER HOST DENGAN SYNTAX:
php artisan route:clear
php artisan config:clear
php artisan cache:clear

B. DAN BILA PERLU AGAR MERUBAH PERMISSION PADA FOLDER STORAGE DAN FOLDER bootstrap/cache KE PERMISSION PUBLIK:
Cara ini bersifat opsional, karena permission juga bisa diatur pada CPANEL.

C. PASTIKAN AGAR CHECKLIST SETTINGAN PADA CPANEL "SHOW HIDDEN FILE .dotfiles" PADA KANAN ATAS.
S
1. INSTALASI LARAVEL PADA SOFTACULUS
2. UPLOAD DAN EKSTRAK FILE PROJECT LARAVEL KE FOLDER INSTALASI LARAVEL
3. SETTING DB PADA MYSQL CPANEL, SESUAIKAN USERNAME,PASS,NAMA DB PADA config>database.php
4. SETTING URL MENJADI NAMA DOMAINNYA, PERGI KE config>app.php pada bagian APP_URL (LINE 55)
5. PASTIKAN FILE .htaccess sudah ada. yang berisi:

<IfModule mod_rewrite,c>
RewriteEngine On 
RewriteRule ^(.*)$ public/$1 [L] 
</IdModule>

<IfModule mime_module>
  AddHandler application/x-httpd-ea-php73___lsphp .php .php7 .phtml
</IfModule>

6. PASTIKAN FILE .env sudah ada (jika belum generate pada host lalu upload terpisah).
```

# Deploy pada VPS
```
Untuk deploy menggunakan VPS silahkan baca Repo WEB Lumen, cara deploy sama saja. Atau bisa baca Repo Docker-Laravel-Certbot.
```
