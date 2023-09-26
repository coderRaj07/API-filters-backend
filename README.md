<!DOCTYPE html>
<html>
<head>
    <title>Product API Documentation</title>
</head>
<body>
    <h1>Welcome to the Product API</h1>
    
    <p>This API allows you to retrieve a list of products with various filtering options. You can search for products, filter by price, and even filter by featured status.</p>

    <h2>Example APIs for Local Machines</h2>

    <p>Here are some example API requests you can make to your local server:</p>

    <h3>Multi-select Prices, Search for 'Apple', and Filter by Featured (true)</h3>
    <p>Retrieve products with the search term 'apple', a price of 154, and a price of 1154 that are also featured.</p>
    <code>http://localhost:5000/api?search=apple&featured=true&price=154&price=1154</code>

    <h3>Single Select Price and Search for 'S20'</h3>
    <p>Retrieve products with the search term 'S20' and a price of 505.</p>
    <code>http://localhost:5000/api?search=S20&price=505</code>

    <h2>Running the App</h2>

    <p>To run the app locally, follow these steps:</p>

    <ol>
        <li>Install the required dependencies using npm:</li>
    </ol>

    ```shell
    npm install
    ```

    <ol start="2">
        <li>Start the local server:</li>
    </ol>

    ```shell
    npm start
    ```

    <p>Once the server is running, you can access the API at <code>http://localhost:5000/api</code>.</p>

    <h2>Adding Filters</h2>

    <p>To apply filters to the API request, you can add query parameters to the URL. Here are some available filters:</p>

    <ul>
        <li><strong>search</strong>: Search for products by name or company.</li>
        <li><strong>price</strong>: Filter by price. You can select a single price or multiple price values.</li>
        <li><strong>featured</strong>: Filter by featured status (true or false).</li>
        <li><strong>page</strong>: Specify the page number for pagination.</li>
        <li><strong>perPage</strong>: Specify the number of products per page.</li>
    </ul>

    <p>For example, to search for products with the name 'apple' that are featured and have prices of 154 and 1154, you can use the following URL:</p>

    <code>http://localhost:5000/api?search=apple&featured=true&price=154&price=1154</code>

    <p>Feel free to explore and customize the API using these filters to get the data you need.</p>

    <p>Thank you for using the Product API!</p>
</body>
</html>
