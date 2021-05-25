# class_booking
final year project for booking class venues

Clone the repository

    git clone https://github.com/Dorice-Kagisa/class_booking.git
Switch to the repo folder

    cd class_booking

Install all the dependencies using composer

    composer install

Copy the example env file and make the required configuration changes in the .env file

    cp .env.example .env

Generate a new application key

    php artisan key:generate

Run the database migrations (**Set the database connection in .env before migrating**)

    php artisan migrate 

Seed data to the table
    php artisan db:seed
Start the local development server

    php artisan serve
