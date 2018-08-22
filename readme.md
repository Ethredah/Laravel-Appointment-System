## About 
This is a simple passport appointment system build with the Laravel Web Framework.
<br>
The application demonstrates creating a new appointment, editing an existing appointment, deleting appointment, reading/ viewing all appointments and pagination.


### Tutorial

<h6>Step 1</h6>
>>Configure Laravel 5.6

`composer create-project --prefer-dist laravel/laravel passportappointmentsystem`


<h6>Step 2</h6>
>>Configure Database in the .env file

`
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=databasename
DB_USERNAME=root
DB_PASSWORD=
`

<h6>Step 3</h6>
>>Migrate the two tables provided by Laravel and type the following command on terminal.

`php artisan migrate
`

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

