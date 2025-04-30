# Laravel Posts CRUD API

A simple RESTful API built with Laravel for managing blog posts. This API supports the basic CRUD operations: Create, Read, Update, and Delete posts.

## Features

- Retrieve all posts
- Retrieve a single post by ID
- Create a new post
- Update an existing post
- Delete a post
- JSON response format with a custom API response trait
- API Resource for consistent data formatting

## Requirements

- PHP >= 7.3
- Laravel >= 8
- Composer
- MySQL or any other supported DB

## Installation

```bash
git clone https://github.com/your-username/laravel-posts-api.git
cd laravel-posts-api
composer install
cp .env.example .env
php artisan key:generate
# Set your database credentials in .env
php artisan migrate
php artisan serve
