A simple e-commerce project using laravel 5
Cloned from https://github.com/leantony/ecommerce.git
To get the project up and running on your local machine, do the following. I assume you already know how to go about laravel, bower composer and npm, so i'll be brief

- clone it => git clone https://github.com/sahilsharma011/ecom-demo.git
- Run composer install, to install dependencies
- Run npm install to install npm dependencies
- Run bower install to install bower dependencies
- Edit the created .env file at the root of your project, to add database credentials, etc
```bash
php artisan key:generate
```
- create your DB and run the migrations, and database seeders found in the migrations folder, using the commands below
```bash
# run all migrations
php artisan migrate
# seed the database. seed data isn't available just yet, but will be added soon
php artisan db:seed
# minify all frontend assets
gulp default
```

- Once the assets are published, run the command
```bash
php artisan serve
```
- visit the site at localhost:8000

- NB# This is a project for course, copied from https://github.com/leantony/ecommerce.git, trying to get grades without doing anything.
