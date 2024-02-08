# WEBSITE

### French 

Ce projet Laravel est un site web. 

### English

This Laravel project is a website.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Development](#development)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Introduction

### French 

C'est un projet Laravel qui utilise Blade et Sass pour le front-end. L'outil Gulp est utilisé pour compiler les fichiers Sass en CSS et pour minifier les fichiers JS et CSS. Le projet utilise également MySQL pour les données envoyées par le formulaire de contact.

### English

This is a Laravel project that uses Blade and Sass for the front-end. The Gulp tool is used to compile Sass files into CSS and to minify JS and CSS files. The project also uses MySQL for the data sent by the contact form.

## Features

- Contact form

## Requirements

- PHP 8.1
- Composer
- Node.js and npm
- MySQL
- Gulp
- Sass

## Installation

1. Clone the repository.
   ```bash
   git clone https://github.com/QuentinMacheda/chateau-beyrin.git
   ```

2. Install PHP dependencies.
    ```bash
    composer install
    ```

3. Install Node.js dependencies.
    ```bash
    npm install
    ```

4. Copy the .env.example file to .env
    ```bash
    cp .env.example .env
    ```

5. Generate the application key.
    ```bash
    php artisan key:generate
    ```

6. Run database migrations.
    ```bash
    php artisan migrate
    ```

7. Compile assets with Gulp.
    ```bash
    gulp
    ```

8. Start the development server.
    ```bash
    php artisan serve
    ```

## Development

### Running tests

You run make tests with this command :
    ```bash 
        php artisan test
    ```

## Contributing

We welcome contributions from the community to improve the project. Whether you want to report a bug, propose a new feature, or contribute code, please follow the guidelines below.

### Issue Reporting

If you find any issues or have suggestions, please open an issue on the [issue tracker](https://github.com/QuentinMacheda/chateau-beyrin/issues). Provide a clear and detailed description of the problem or enhancement you're suggesting.

### Pull Requests

If you'd like to contribute code, you can submit a pull request. Follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.
   ```bash
   git checkout -b feature/new-feature
   ```
   or

   ```bash
   git checkout -b bugfix/fix-issue
    ```

3. Make your changes and commit them with clear and concise messages.
    ```bash
    git commit -m "Add new feature"
    ```

4. Push your branch to your fork on GitHub.

5. Open a pull request on the pull request page of the original repository.

Provide a descriptive title and explain the purpose of your changes.
Reference any related issues.

### Coding Standards

Before submitting a pull request, make sure your code adheres to the project's coding standards. Run any relevant tests and update documentation as needed.



Thank you for contributing to our project!
