DummyJSON API - Your Ultimate Source for Fictional Products

Welcome to DummyJSON API, where creativity meets the virtual world of product data! 🚀 In this playground, we provide a curated collection of imaginative product information to fuel your testing and development needs. Explore the realm of non-existent products with ease!

Endpoints
Get All Products
http
Copy code
GET /products
Retrieve a list of fascinating imaginary products.

Get Product by ID
http
Copy code
GET /products/{id}
Fetch detailed information about a specific product using its unique identifier.

Example Product Data
json
Copy code
{
  "products": [
    {
      "id": 1,
      "title": "iPhone 9",
      "description": "An apple mobile which is nothing like apple",
      "price": 549,
      "discountPercentage": 12.96,
      "rating": 4.69,
      "stock": 94,
      "brand": "Apple",
      "category": "smartphones",
      "thumbnail": "https://cdn.dummyjson.com/product-images/1/thumbnail.jpg",
      "images": [
        "https://cdn.dummyjson.com/product-images/1/1.jpg",
        "https://cdn.dummyjson.com/product-images/1/2.jpg",
        "https://cdn.dummyjson.com/product-images/1/3.jpg",
        "https://cdn.dummyjson.com/product-images/1/4.jpg",
        "https://cdn.dummyjson.com/product-images/1/thumbnail.jpg"
      ]
    },
    {
      "id": 2,
      "title": "iPhone X",
      "description": "SIM-Free, Model A19211 6.5-inch Super Retina HD display with OLED technology A12 Bionic chip with ...",
      "price": 899,
      "discountPercentage": 17.94,
      "rating": 4.44,
      "stock": 34,
      "brand": "Apple",
      "category": "smartphones",
      "thumbnail": "https://cdn.dummyjson.com/product-images/2/thumbnail.jpg",
      "images": [
        "https://cdn.dummyjson.com/product-images/2/1.jpg",
        "https://cdn.dummyjson.com/product-images/2/2.jpg",
        "https://cdn.dummyjson.com/product-images/2/3.jpg",
        "https://cdn.dummyjson.com/product-images/2/thumbnail.jpg"
      ]
    }
  ]
}
Sample Requests
Get All Products
bash
Copy code
curl https://programmerof.github.io/dummyjson/products
Get Product by ID
bash
Copy code
curl https://programmerof.github.io/dummyjson/products/1
Explore and Have Fun!
Feel free to integrate DummyJSON into your projects and let your creativity flow. Create engaging user interfaces or test your application's resilience with our imaginative data. The possibilities are endless! Happy coding! 🚀✨
