
## About this Repository

> This is Laravel Migration and Seeder files for the Nigeria States and Local Governments


### How to use this Files



#### Step 1 - Create State and Local Government Models in your laravel application

` php artisan make:model State `
` php artisan make:model LocalGovernment `



#### Step 2 - Download this repo as zip and extract files


[Download this repo from this link](https://github.com/KingAdeCode/Nigeria-States-and-Local-Governments-Laravel-Seeder/archive/refs/heads/main.zip)



#### Step 3 - Copy Files into your Laravel Application

Copy the two folders 'seeders' and 'migrations' into your laravel application



#### Step 4 - Add the two files to DatabaseSeeder.php under your Seeders folder

`
$this->call(StateSeeder::class);
$this->call(LocalGovernmentSeeder::class);
`
Setup your DB in .env file then run 

`php artisan migrate'
