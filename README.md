
## Installation
```
git clone https://github.com/lovecoding-git/laravel-inertia
cd laravel-inertia
cp -r .env.example .env

#for production
composer install --no-dev --optimize-autoloader

#for dev
composer install
php artisan migrate

npm install
npm run dev
```