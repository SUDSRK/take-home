# Food Darzee Backend-focused Exercise
___

```
TIME LIMIT: 8-9 hours max. We mean it! Set a timer and hard-stop at 8 hours ⏱
LANGUAGES:  PHP 7, Python etc
FRAMEWORKS: Yii2 (Prefered), Laravel, Django etc
DATABASE:   MySQL/MariaDB, Postgres etc
TESTS:      nice to have, but not mandatory
DOCS:       nice to have, but not mandatory
```

## Overview
This exercise is to implement the best possible solution to the exercises below in the time allotted. We're evaluating your ability to take a set of requirements and spike a holistic solution that demonstrates craftsmanship, thoughtfulness and good architectural design. This is **NOT** a test of how well you know Angular/React/Vue, nor should you try to impress us with overly clever and obtuse solutions. If you want to impress us, build something that is beautiful, intuitive and easy to debug/test/extend :smiley: .

Ideally your solution would have some way to run locally and test the results, so we can fully analyze your efforts.

### e-Com
The goal of this exercise is to design, architect a production ready solution for submitting cart, and an admin panel

#### User Story: As a developer I want to

* Calculate the cart price based on the following input (RESTful API Preferred but simple command line code will also work)
    * Inputs:
        * Multiple products
        * Combine offers
        * Response should be the total amount based on the currency user selects
        * The ability for the code to handle special offers
            * Any product type like `Rice` are on 10% Off
            * But two `Pens` and get the third free
    * Output:
        * Sub-total
        * Tax (18% tax before discounts applied to all products.)
        * discounts (if applicable)

``` 
Eg:
    Input:
        Rice
        Rice
        Juice
        Pen
    Output:
        Subtotal: Rs. 66.96
        Taxes: Rs. 9.37
        Discounts:
            10% off Rice: Rs. -2.499
            50% off Pen: Rs. -9.995
        Total: Rs. 63.8404

```

* Admin Panel
    * Dashboard (show some details)
    * CRUD's (CREATE, READ, UPDATE and DELETE) for adding products, currencies, etc 
    * The icon/image should not go out of bounds

### Some notes while submitting your work

* Stick to Object-Oriented fundamentals in all aspects of your code.
* Stick to [SOLID](https://en.wikipedia.org/wiki/SOLID) principles 

## Submitting your work
1. See [instructions for submitting your work](https://github.com/FoodDarzee/take-home#general-instructions)
