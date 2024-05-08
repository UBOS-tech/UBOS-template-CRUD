# Product List Management CRUD Application

This Node-RED template provides a CRUD (Create, Read, Update, Delete) application for managing a product list. It includes several HTTP endpoints to handle different operations:

- **/createProduct**: This endpoint accepts a POST request to create a new product record. It requires the product name, price, and optionally rating in the request body.
- **/getProducts**: This endpoint accepts a GET request to retrieve all product records from the database.
- **/updateProduct**: This endpoint accepts a PUT request to update an existing product record. It requires the product ID and updated fields in the request body.
- **/deleteProduct**: This endpoint accepts a DELETE request to remove a product record from the database by its ID.

Additionally, the template features an AI-powered bulk create feature with the **/AIBulkCreate** endpoint. This endpoint takes a prompt from the user and interacts with the OpenAI API to generate parameters for creating multiple product records based on the prompt and the `/createProduct` API documentation. The generated parameters are then used to make requests to the `/createProduct` endpoint, effectively enabling users to create multiple product records at once using natural language input.

## Database Details

The application uses MongoDB as the database to store product records. The database connection details are configured using environment variables, ensuring flexibility and security in deployment.

This Node-RED template offers a comprehensive solution for managing a product list efficiently, combining traditional CRUD operations with the innovative use of AI-powered natural language processing for bulk creation.
