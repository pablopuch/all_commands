# Laravel Commands

## Table of Contents

- [Create new project](#create-new-project)
- [Check Laravel version](#check-laravel-version)
- [Run the server](#run-the-server)
- [Create a migration table](#create-a-migration-table)
- [Run migrations](#run-migrations)
- [Rollback the last migration](#rollback-the-last-migration)
- [Create a model](#create-a-model)
- [Create a factory](#create-a-factory)
- [Refresh migrations](#refresh-migrations)
- [Run seeders](#run-seeders)
- [Refresh migrations and seed](#refresh-migrations-and-seed)
- [Create a controller](#create-a-controller)
- [Create a controller with functions](#create-a-controller-with-functions)
- [List all routes](#list-all-routes)
- [Create a validation request](#create-a-validation-request)
- [Run tests](#run-tests)
- [Run a server on specific IP](#run-a-server-on-specific-ip)
- [Create a test file](#create-a-test-file)
- [Clear cache](#clear-cache)
- [Clear route cache](#clear-route-cache)
- [Clear config cache](#clear-config-cache)
- [Clear view cache](#clear-view-cache)
- [Reoptimize cache](#reoptimize-cache)

## Create new project

Create project: 

```
composer create-project laravel/laravel name-project
```

## Check Laravel version

Check the Laravel version: 
```
php artisan --version
```

## Run the server

Start the Laravel development server: 
```
php artisan serve
```

## Create a migration table

Create a migration table: 
```
php artisan make:migration name-table --create=passworks
```

## Run migrations

Run database migrations: 
```
php artisan migrate
```

## Rollback the last migration

Rollback the last migration that was executed: 
```
php artisan migrate:rollback
```

## Create a model

Create a model: 
```
php artisan make:model name-model
```

## Create a factory

Create a factory: 
```
php artisan make:factory name-factory --model=Passwork
```

## Refresh migrations

Refresh all migrations: 
```
php artisan migrate:fresh
```

## Run seeders

Run the seeders: 
```
php artisan db:seed
```

## Refresh migrations and seed

Refresh migrations and run seeders: 
```
php artisan migrate:fresh --seed
```

## Create a controller

Create a controller: 
```
php artisan make:controller name-controller
```

## Create a controller with functions

Create a controller with predefined API functions: 
```
php artisan make:controller name-controller --api
```

## List all routes

List all routes: 
```
php artisan route:list
```

## Create a validation request

Create a validation request: 
```
php artisan make:request name-file
```

## Run tests

Run the tests: 
```
php artisan test
```

## Run a server on specific IP

Run the Laravel development server on a specific IP: 
```
php artisan serve --host 0.0.0.0
```

## Create a test file

Create a test file: 
```
php artisan make:test name-file
```

## Clear cache

Clear the application cache: 
```
php artisan cache:clear
```

## Clear route cache

Clear the route cache: 
```
php artisan route:clear
```

## Clear config cache

Clear the config cache: 
```
php artisan config:clear
```

## Clear view cache

Clear the compiled view files cache: 
```
php artisan view:clear
```

## Reoptimize cache

Reoptimize the cache: 
```
php artisan optimize:clear
```
