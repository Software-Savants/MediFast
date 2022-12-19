# MediFast
MediFast is a web app for fast and convenient medicine delivery. It allows users to browse and select from a list of available doctors, view their specialties and hours of operation, and schedule appointments with them. The app also allows users to place orders for medicine delivery and track the status of their orders in real-time.

## Prerequisites
* PHP 7.4 or higher
* MySQL or MariaDB database
* Redis in-memory data store
* Node.js and npm
* Laravel 8.x

## Installation
1. Clone the repository: `git clone https://github.com/Software-Savant/MediFast.git`
1. Install dependencies: `composer install` and `npm install`
1. Set up the database: `cp .env.example .env` and  `php artisan key:generate`
1. Update the .env file with your database credentials. Then run the migrations: `php artisan migrate`
1. Build the frontend assets: `npm run dev`
1. Start the development server: `php artisan serve`

## Usage
To use the app, visit http://localhost:8000 in your web browser.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

