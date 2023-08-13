
This project runs with Laravel version 10.10.

## Getting started

Assuming you've already installed on your machine: PHP (>= 8.1), [Laravel](https://laravel.com), [Composer](https://getcomposer.org)

``` bash
# install dependencies
composer install


# create .env file and generate the application key
cp .env.example .env
php artisan key:generate

# cronjob command
php artisan create:document-diffs

```

Then launch the server:

``` bash
php artisan serve
```

The Document Management project is now up and running! Access it at http://localhost:8000.


## Others Features Registration and Login. Here I add api route with paramatter

#### http://127.0.0.1:8000/api/register
Example Data: 
    {
        "name" : "istiake",
        "email" : "istiake@gmail.com",
        "password" : "istiake123456@",
        "password_confirmation": "istiake123456@"
  
    } 

#### http://127.0.0.1:8000/api/login
Example Data: 
    {
        "email" : "istiake@gmail.com",
        "password" : "istiake123456@",
    } 

# document-management
