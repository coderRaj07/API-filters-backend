## Product API Documentation

Welcome to the Product API, which provides various filtering options for retrieving product information. You can search for products, filter by price, and even filter by featured status.

<details open="">
  
  Example APIs for Local Machines

  Here are some example API requests you can make to your local server:

  **Multi-select Prices, Search for 'Apple', and Filter by Featured (true)**

  Retrieve products with the search term 'apple', a price of 154, and a price of 1154 that are also featured.
  
   http://localhost:5000/api?search=apple&featured=true&price=154&price=1154
  
  **Single Select Price and Search for 'S20'**
  
  Retrieve products with the search term 'S20' and a price of 505.
  
   http://localhost:5000/api?search=S20&price=505
   
</details>


## Running the App

To run the app locally, follow these steps:

1. Install the required dependencies using npm.
```npm i```
2. Start the local server.
```npm run dev```


Once the server is running, you can access the API at 

http://localhost:5000/api.

## Adding Filters
To apply filters to the API request, you can add query parameters to the URL. Here are some available filters:

- **search**: Search for products by name or company.
- **price**: Filter by price. You can select a single price or multiple price values.
- **featured**: Filter by featured status (true or false).
- **page**: Specify the page number for pagination.
- **perPage**: Specify the number of products per page.

For example, to search for products with the name 'apple' that are featured and have prices of 154 and 1154, you can use the following URL:

http://localhost:5000/api?search=apple&featured=true&price=154&price=1154

Feel free to explore and customize the API using these filters to get the data you need.


<p align="center">Thank you for using the Product API!</p>
```
