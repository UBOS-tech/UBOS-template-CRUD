UBOS-template-CRUD
==============
<p align="center">
  <img width="50%" align="center" alt="Ubos - End-to-End Software Development Platform" src="https://ubos.tech/wp-content/uploads/2023/03/cropped-Group-21015-1.png">
</p>

<h3 align="center">
  <b><a href="https://documentation.ubos.tech/docs/intro">Get Started</a></b>
  •
  <a href="https://community.ubos.tech/">Community</a>
  •
  <a href="https://www.youtube.com/@ubos_tech">Youtube</a>
  •
  <a href="https://discord.com/invite/dt59QaptH2">Discord</a>
  •
  <a href="https://github.com/UBOS-tech">GitHub</a>
  </h3>

<div align="center">
  
  [![Use template](https://ubos.tech/wp-content/uploads/2023/06/download-logo.png)](https://ubos.tech/listing/ai-powered-product-list-manager/)
  
</div>

# Product List Management CRUD Application

This Node-RED template provides a CRUD (Create, Read, Update, Delete) application for managing a product list. It includes several HTTP endpoints to handle different operations:

- **/createProduct**: This endpoint accepts a POST request to create a new product record. It requires the product name, price, and optionally rating in the request body.
- **/getProducts**: This endpoint accepts a GET request to retrieve all product records from the database.
- **/updateProduct**: This endpoint accepts a PUT request to update an existing product record. It requires the product ID and updated fields in the request body.
- **/deleteProduct**: This endpoint accepts a DELETE request to remove a product record from the database by its ID.

<img width="1440" alt="CRM" src="https://ubos.tech/wp-content/uploads/2024/05/Screenshot_2-1.png">

Additionally, the template features an AI-powered bulk create feature with the **/AIBulkCreate** endpoint. This endpoint takes a prompt from the user and interacts with the OpenAI API to generate parameters for creating multiple product records based on the prompt and the `/createProduct` API documentation. The generated parameters are then used to make requests to the `/createProduct` endpoint, effectively enabling users to create multiple product records at once using natural language input.

## Database Details

The application uses MongoDB as the database to store product records. The database connection details are configured using environment variables, ensuring flexibility and security in deployment.

This Node-RED template offers a comprehensive solution for managing a product list efficiently, combining traditional CRUD operations with the innovative use of AI-powered natural language processing for bulk creation.

## Features

### User-Friendly CRUD Operations
- **Create**: Easily create new product records by providing essential details such as name, price, and optional rating. Your data is securely stored in MongoDB.
- **Read**: Retrieve a comprehensive list of all your products, ensuring you have complete visibility of your inventory.
- **Update**: Effortlessly modify existing product details to keep your data accurate and up-to-date.
- **Delete**: Streamline your inventory by removing obsolete or unwanted products from your list with just a few clicks.

### AI-Powered Bulk Creation
- **Efficient**: Describe the products you need, and our advanced AI technology, powered by OpenAI, generates the necessary parameters based on API documentation.
- **Time-Saving**: Save time by creating multiple product records at once using natural language input.
- **Consistent and Accurate**: Ensure consistency and accuracy in your product data with automated bulk creation.

<img width="1440" alt="CRM" src="https://ubos.tech/wp-content/uploads/2024/05/Screenshot_1-1.png">
