# Ice-FireClone
Ice and Fire API clone

## Framwork
  Php Laravel 

## REQUIRMENTS
1. Postman or any API managment tool
2. Composer 
3. MYSQL database 

## SETUP/CONFIGURATION
1. Clone or download this repo
2. Run composer install from the terminal in the root directory to install packages and dependecies
3. Create a database and change database configuration in the .env file located in the root directory
4. Run the artisan command; php artisan migrate to automatically create tables already setup in the migration file
5. Run the artisan command; php artisan serve from the terminal in the root directory to start the php server
6. Copy the url displayed in the terminal and enter in your browser or Postman
7. To run test; run the artisan command; php artisan test from the terminal in the root directory

## ROUTES
1. Create => /api/v1/books
2. Show => /api/v1/books/{bookId}
3. Update => /api/v1/books/{bookId}
4. Delete => /api/v1/books/{bookId} 
5. List books => /api/v1/books
5. external books (Ice and Fire API) =>  /api/v1/external-books/{bookName}
