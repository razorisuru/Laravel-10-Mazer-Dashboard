# Mazer Dashboard

# Using Laravel 10

# Dashboard

## Installation

1. Clone this project
    ```bash
    git clone https://github.com/razorisuru/Larvel-10-Mazer-Dashboard
    ```
2. Install dependencies

    ```bash
    composer install
    ```

    And javascript dependencies

    ```bash
    yarn install && yarn dev

    #OR

    npm install && npm run dev
    ```

3. Set up Laravel configurations

    ```bash
    copy .env.example .env
    php artisan key:generate
    php artisan storage:link
    ```

4. Set your database in .env

5. Migrate database

    ```bash
    php artisan migrate
    ```

6. Build the application

    ```bash
    npm run build
    npm run dev
    ```

7. Serve the application

    ```bash
    php artisan serve
    ```
