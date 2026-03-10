# fastapi-day2-assignment
# FastAPI Day 2 Assignment

This repository contains the solutions for the **FastAPI Day 2 Practice Tasks** from the internship training program.

## Project Description

The assignment demonstrates basic API development using **FastAPI**, including:

* Creating GET endpoints
* Using query parameters
* Handling path parameters
* Implementing POST requests
* Data validation using Pydantic models
* Business logic implementation for API responses

## Implemented Endpoints

1. **Filter Products**

   * Endpoint: `/products/filter`
   * Filters products based on minimum price, maximum price, and category.

2. **Get Product Price**

   * Endpoint: `/products/{product_id}/price`
   * Returns only the name and price of a specific product.

3. **Customer Feedback**

   * Endpoint: `/feedback`
   * Accepts customer feedback using a POST request with validation.

4. **Product Summary**

   * Endpoint: `/products/summary`
   * Provides summary statistics such as total products, stock availability, most expensive and cheapest products, and categories.

5. **Bulk Order Processing**

   * Endpoint: `/orders/bulk`
   * Processes multiple order items, validates product availability, and calculates total cost.

## Technologies Used

* Python
* FastAPI
* Uvicorn
* Pydantic

## How to Run the Project

1. Install dependencies

```
pip install fastapi uvicorn
```

2. Run the server

```
uvicorn main:app --reload
```

3. Open Swagger UI

```
http://127.0.0.1:8000/docs
```

## Author

Himanshu Shekhar Singh
