## About TTI Project Management

This is my solution to the coding challenge presented by [TTI](https://tti.care).

## Run the Local Environment via Laravel Sail

Sail on MacOS was used via issuing the command:

`curl -s "https://laravel.build/tti-project-management" | bash`

To run the application locally, follow the steps below:

`cd /pathToProject/localName`

`./vendor/bin/sail up -d`

## Set-Up the Migrations and Seeders

Add the table by running:

`./vendor/bin/sail artisan migrate`

Add the test data by issuing the commands:

`./vendor/bin/sail artisan db:seed --class=ProjectSeeder`

`/vendor/bin/sail artisan db:seed --class=TaskSeeder`