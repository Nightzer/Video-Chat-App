## Video Chat App
CREDITS

[Youtube Tutorial link](https://www.youtube.com/watch?v=5pnsloZzYQM)

#### [@WeCodeTutorials](https://twitter.com/WeCodeTutorials)


This project is based on a youtube tutorial. Made with with Laravel, ReactJS and WebRTC.

## Installation.

After you clone this project, do the following:

```bash
# create a .env file
cp .env.example .env

# install composer dependencies
composer update

# install npm dependencies
npm install

# generate a key for your application
php artisan key:generate

# create a file for your SQLite database
touch database/database.sqlite

# mrun the migration files to generate the schema
php artisan migrate

# run webpack and watch for changes
npm run watch
```
