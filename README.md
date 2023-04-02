<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>


## Migrations

To create all the nessesary tables and columns, run the following

`php artisan migrate`

## Seeding The Database

To add the dummy listings with a single user, run the following

`php artisan db:seed`

## File Uploading

When uploading listing files, they go to "storage/app/public". Create a symlink with the following command to make them publicly accessible.

`php artisan storage:link`

## Running The App

Upload the files to your document root, Valet folder or run

`php artisan serve`

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
