# FullStackVueWithLaravelRESTfulAPI2


# Install Dependencies
composer install

# Run Migrations
php artisan migrate

# Import Articles
php artisan db:seed

# Add virtual host if using Apache

# If you get an error about an encryption key
php artisan key:generate

# Install JS Dependencies
npm install

# Watch Files
npm run watch


# Additional to make it run after clone
on clone make sure you change .env.example > .env
(inside laravel project) php artisan key:generate

source: https://stackoverflow.com/questions/53029422/cloned-laravel-project-and-install-composer-and-npm-then-also-give-me-error-500
