# Yassin Facebook

### Tutorial showing you how to build Facebook


## App Setup

```
git clone https://github.com/John-Weeks-Dev/facebook-clone.git

composer install 

copy .env.example .env 

php artisan cache:clear 

composer dump-autoload 

php artisan key:generate

composer require laravel/breeze --dev

php artisan breeze:install vue --ssr

php artisan serve
```
Create the DB
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=facebook_clone
DB_USERNAME=root
DB_PASSWORD=
```
Now migrate your DB
```
php artisan migrate

php artisan db:seed
```

Now run this command to start the project 
```
npm i

npm run dev
```

You should be good to go!
