# Articles Web App

This is a web application for managing articles. It allows users to create, read, update, and delete articles, and provides features such as pagination, search, sorting, image upload, and authentication.

## Technologies Used

- Laravel
- PHP
- MySQL (or your preferred database)
- HTML
- CSS (with Tailwind CSS)

## Key Features and Functionalities

- Create, read, update, and delete articles
- Pagination for displaying a limited number of articles per page
- Search functionality to find articles by title or content
- Sorting of articles by title or published date
- Image upload for articles
- User authentication and authorization

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/AbdelazizHanzaz/laravel_articles_web_app.git
   
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
   
