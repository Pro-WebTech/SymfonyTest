# Football Team Management App

This is a Symfony PHP application that allows users to manage football teams, players, and player transfers.

## Getting Started

To get started with the app, you'll need to do the following:

1. Clone the repository to your local machine.
```bash
git clone https://github.com/TechAriSet/SymfonyTest.git
```
2. Install the required dependencies using Composer.
```bash
composer install
```
3. Run database migrations to create the necessary tables in your database.
```bash
php bin/console doctrine:migrations:migrate
symfony server:start
```

Once you've completed these steps, you should be ready to start using the app.

## Features

The app provides the following features:

- Display all teams and their players on a paginated page.
- Add a new team and its players on a separate page.
- Buy/sell a player between two teams for a certain amount on another page.

## Usage

To use the app, simply navigate to the appropriate page using your web browser. From there, you can perform the desired action.

