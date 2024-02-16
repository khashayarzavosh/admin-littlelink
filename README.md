
This project will no longer be updated, use its new fork and donate to me with USDT.

USDT(BEP20): 0x2A4eE50b2bf51c38Fe66120695976be493FcE8fF

https://github.com/LinkStackOrg/LinkStack

## _⚙️ LittleLink Admin_

LittleLink Admin is an admin panel for [littlelink] that provides you a website similar [linktree].

## 📑 Features

- creating a link page with more than 20 buttons
- raising important links on the page
- counting clicks
- managing users and pages and links
- and ...

## ✨ Demo

[home] / [panel]

## 🔨 Install

```sh
composer create-project khzg/littlelink-admin
```

- edit .env file

DB_DATABASE=YOUR_DATABASE_NAME

DB_USERNAME=YOUR_USERNAME

DB_PASSWORD=YOUR_PASSWORD

APP_NAME="Littlelink admin"

```sh
cd littlelink-admin
php artisan migrate
php artisan db:seed 
(or commands below)
php artisan db:seed --class="AdminSeeder"
php artisan db:seed --class="PageSeeder"
php artisan db:seed --class="ButtonSeeder"
php artisan serve
```

- login:

email: admin@admin.com

password: 12345678

## 💞 Partners

- [littlelink]
- [laravel]
- [panel template]

## 🎲 [Donate](#donate)

USDT(BEP20): 0x2A4eE50b2bf51c38Fe66120695976be493FcE8fF

   [littlelink]: <https://github.com/sethcottle/littlelink>
   [linktree]: <https://linktr.ee>
   [home]: <https://github.com/khzg/littlelink-admin/blob/main/demo-home.png>
   [panel]: <https://github.com/khzg/littlelink-admin/blob/main/demo-panel.png>
   [laravel]: <https://github.com/laravel/laravel>
   [panel template]: <https://colorlib.com/wp/bootstrap-sidebar>
