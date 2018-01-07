In order to run the project, execute the following steps:

    Clone/Checkout this repo. (git clone $urlLink)
    Install composer if needed.
    Open a cmd in the project folder.
    Run "composer install" to install dependencies.
    Locate and open env.example file.
    Edit DB_DATABASE, DB_USERNAME, DB_PASSWORD to match yours.
    Rename .env.example to .env;
    In the CLI(cmd/terminal) run "php artisan key:generate" to add an app key to your .env file.
    Run "php artisan serve" to run the project.
