# codechallenge1phase4
# Week 1 Code Challenge 
# Flask Code Challenge - Pizza Restaurants
In this code challenge, you will be building a Flask API for a Pizza Restaurant domain. The API will include various functionalities related to restaurants, pizzas, and their associations. Below, you will find the details of the tasks to be completed and how to run and test your Flask application.
# Requirements
To run this project, you will need:

Python 3.x
Flask
SQLAlchemy
Flask-Migrate
Flask-RESTful
Faker (optional, for seeding data)
Postman (optional, for testing API endpoints)
## API Endpoints
The API includes the following endpoints:

GET /restaurants: Returns a list of restaurants.

GET /restaurants/:id: Returns details of a specific restaurant by ID, including its associated pizzas.

DELETE /restaurants/:id: Deletes a restaurant by ID, along with its associated restaurant-pizza relationships.

GET /pizzas: Returns a list of available pizzas.

POST /restaurant_pizzas: Creates a new restaurant-pizza relationship.



## Data Models
The project includes the following data models:

Restaurant: Represents a pizza restaurant with a name, address, and a collection of associated pizzas.

Pizza: Represents a type of pizza with a name, list of ingredients, and a collection of associated restaurants.

RestaurantPizza: Represents a relationship between a restaurant and a pizza, including the price of the pizza at that restaurant.

## Validations
The API enforces the following validations:

Restaurant names must be less than 50 characters in length and must be unique.

RestaurantPizza prices must be between 1 and 30.

## Testing
You can test the API endpoints using Postman or any other API testing tool. Ensure that the Flask server is running before sending requests.
## Support and contact details 
To make a contribution to the code used or any suggestions you can click on the contact link and email me your suggestions.
    • Email: kipkorirc583@gmail.com
## License
 Copyright (c) 2023 Collins Kipkorir.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files , to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

