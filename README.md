In order to run the project, execute the following steps:

1. Clone/Checkout this repo. (git clone $urlLink)
2. Install composer if needed.
3. Install XAMPP/WAMPP or PhP and Apache.
4. Create а new empty database.
5. Open a cmd in the project folder.
6. Run "composer install" to install dependencies.
7. Locate and open env.example file.
8. Edit DB_DATABASE, DB_USERNAME, DB_PASSWORD to match yours.
9. Rename .env.example to .env;
10. In the CLI(cmd/terminal) run "php artisan key:generate" to add an app key to your .env file.
11. Run "php artisan serve" to run the project.
