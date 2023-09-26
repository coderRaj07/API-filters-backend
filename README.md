<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product API</title>
</head>
<body>
    <h1>Product API</h1>
    
    <p>Welcome to the Product API documentation. This API allows you to retrieve products based on various filters and search criteria.</p>

    <h2>Example APIs for Local Machines</h2>

    <p>Here are some example API calls you can make to this API on your local machine:</p>

    <h3>Multiselect Prices, Search for 'Apple', and Featured Products</h3>
    <pre><code>GET http://localhost:5000/api?search=apple&featured=true&price=154&price=1154</code></pre>

    <p>This API call will return products that match the following criteria:</p>
    <ul>
        <li>Search term: 'Apple'</li>
        <li>Featured products: true</li>
        <li>Price options: 154 and 1154</li>
    </ul>

    <h3>Single Select Price and Search for 'S20'</h3>
    <pre><code>GET http://localhost:5000/api?search=s20&price=505</code></pre>

    <p>This API call will return products that match the following criteria:</p>
    <ul>
        <li>Search term: 'S20'</li>
        <li>Price options: 505</li>
    </ul>

    <h2>How to Run the App</h2>

    <p>Follow these steps to run the application locally:</p>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/your/repo.git</code></pre>

        <li>Install the dependencies:</li>
        <pre><code>npm install</code></pre>

        <li>Start the server:</li>
        <pre><code>npm start</code></pre>

        <li>Access the API:</li>
        <pre><code>http://localhost:5000/api</code></pre>
    </ol>

    <p>Once the server is running, you can add filters to the API URL as shown in the example APIs above.</p>

    <h2>API Filters</h2>

    <p>The API supports the following filters:</p>
    <ul>
        <li><strong>search</strong>: Search for products by name or company.</li>
        <li><strong>price</strong>: Filter by price (single or multiple values).</li>
        <li><strong>featured</strong>: Filter by featured products (true or false).</li>
        <li><strong>page</strong>: Specify the page number for pagination (default: 1).</li>
        <li><strong>perPage</strong>: Specify the number of products per page (default: 10).</li>
    </ul>

    <p>If you have any questions or encounter any issues, please refer to the API documentation or contact the API developer.</p>
</body>
</html>
