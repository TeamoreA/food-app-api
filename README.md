# orders-api

 ###### This is an API having endpoints to get a list of all order items, get a singe order item by specifying its id, update an order item and finally can delete the order item .


[![Build Status](https://travis-ci.com/TeamoreA/app-api.svg?branch=develop)](https://travis-ci.com/TeamoreA/app-api)
[![Test Coverage](https://api.codeclimate.com/v1/badges/a99a88d28ad37a79dbf6/test_coverage)](https://codeclimate.com/github/codeclimate/codeclimate/test_coverage)
[![Maintainability](https://api.codeclimate.com/v1/badges/a99a88d28ad37a79dbf6/maintainability)](https://codeclimate.com/github/codeclimate/codeclimate/maintainability)

## Aimed Functionalities Endpoints 
- A user can view all orders
- A user can view a specific order.
- A user can create an order.
- A user can update an order.
- A user can delete an order.

## How to use it

- Clone the repo [HERE](https://github.com/TeamoreA/orders-api).
- Install all the depedencies in requirements.txt
- Run the file orders.py (python orders.py)
- Using Postman app to test the endpoints
    ##To see all orders run the GET route - http://127.0.0.1:5000/api/v1/orders
    ##To see one order run the GET route - http://127.0.0.1:5000/api/v1/orders/(1)
    ##To see create an order run the POST route - http://127.0.0.1:5000/api/v1/orders
    ##To see update an order run the PUT route - http://127.0.0.1:5000/api/v1/orders/(1)
    ##To see delete an order run the DELETE route - http://127.0.0.1:5000/api/v1/orders/(1)
