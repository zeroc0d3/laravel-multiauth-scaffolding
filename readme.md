## Laravel Multi-Auth Scaffolding

Laravel 5.4 Multi-Auth Scaffolding is a "starter kit" you can use to build your first Laravel 5.4 Multi-Auth Application. This is build on top of Laravel 5.4.

You can quickly create an app with standard user login panel and dashboard and Admin login panel and dashboard. 

## Installation

1. run `composer create-project davemin/laravel-multiauth-scaffolding myapp`;

Once the project creation procedure will be completed, run the `php artisan migrate` command to install the required tables.

## Usage

Now you have `users` table and `admins` table, fill with same fake user and admin with password. 
If you login as admin you can access to admin dashboard, instead, if you login as standard user you can use users dashboard.

I currently made this project for personal purposes. If you have any feedback to improve it, feel free to make a suggestion, or open a PR!