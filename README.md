# laravel_articles_web_app
This is a web application built with Laravel that allows users to create, read, update, and delete articles. The app provides a user-friendly interface for managing articles with features such as pagination, search, sorting, image upload, and authentication.
## Installation

1. Clone the repository:

   ```shell
   git clone <repository-url>
   
2. Navigate to the project directory:

   ```shell
   cd articles-web-app

3. Install the dependencies:

   ```shell
   composer install
   
4. Copy the .env.example file to .env:

   ```shell
   cp .env.example .env

5. Generate the application key:
   
    ```shell
   php artisan key:generate
    
6. Configure the database connection in the .env file with your database credentials.

7. Run the database migrations:

     ```shell
   php artisan migrate
   
