# E-0923 NodeJS Exercise - Express.js CRUD

Goal: Create a simple CRUD backend server using Express.js

1. Create a `dev` branch after accepting the assignment
2. Switch to the `dev` branch after cloning the repository to your localhost
3. Set up your Node webserver using Express. Install Express by running `npm install express` on the terminal
4. Create an empty array called `products` which will be your in-memory database
5. Create the routes with the correct methods for each of the CRUD functions:

    - `/products` : GET request for all products
    - `/products` : POST request to add one product
    - `/products/:id` : GET request to fetch one product based on id
    - `/products/:id` : UPDATE request to update one product based on id
    - `/products/:id` : DELETE request to delete one product based on id

6. Start your server by running `node index.js` if your server filename is index.js
7. Use Postman to test your routes [https://www.postman.com/]. Create an account and download the software
8. Once your server is working, push your changes and merge from `dev` to `master/main`