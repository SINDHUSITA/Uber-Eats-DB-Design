# Uber-Eats-DB-Design
CS411 Database Systems Homework 3

Instructions:
You are working for Uber Eats. Your manager tasks you with designing a new database for keeping track of its service. Given the following information, draw the ER diagram:

● The database should store information about Customers, Restaurants, Dishes, Chefs, and Buildings.

● Customers are uniquely identified by their ID. Other customer attributes are name and birthday.

● A Restaurant is uniquely identified by its name and the building it’s located in. Other restaurant attributes are type and size.

● A Dish is uniquely identified by its name and the restaurant that offers it. Other dish attributes are flavor and popularity.

● Chefs are uniquely identified by their SSN. Other chef attributes are name and salary.

● A Building is uniquely identified by its address. It has area as another attribute.

● A Customer may order multiple Dishes, and each Dish may be ordered by multiple Customers.

● Every time a Customer orders a Dish, we want to store information about what date that customer makes the order, specifically the attribute “date”.

● A Dish may be cooked by multiple Chefs, and a Chef may cook multiple Dishes.

● A Dish can only be offered by a single Restaurant, but a Restaurant may offer multiple Dishes.

● A Restaurant may employ multiple Chefs, but each Chef can only work in one Restaurant.

● A Restaurant is located at only one Building, but each Building may have multiple Restaurants.
