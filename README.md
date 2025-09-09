# Kingfisher Shopping Cart Demo

Calculator available at: https://mattlewisgit.github.io/shopping_cart_task/

User Story

Title: Shopping Cart

Description: As a kingfisher user, I want to add products to basket, log in and place an order to prove that my webpage works as expected

Acceptance Criteria

1) I can add all the available products to basket
2) I can remove a single product quantity from basket
3) I can apply a discount using:
- SAVE10 = 10% discount
- SAVE20 = 20% discount
4) I can only checkout with the following credentials:
username: user
password: pass
5) I receive a checkout successful! Thank you for your purchase message


Bugs:

1) you can add and proceed through checkout with more than the stock available
2) you can add discounts from 30% all the way up to 100% (using SAVE30 / SAVE40 ect)
3) checkout without anything is basket!
4) if multiple of the same product in basket, you cannot remove a single quantity.
5) one product is in Dollars
6) unable to add any more than 1 pepper to basket (removes pepper all together)
7) Add Orange to shopping cart, actually adds a banana instead (which is out of stock)
8) If username is correct, and password is empty, then chckout succeeds.
9) Carrot value is £0.60, but in basket is £0.70
10) Carrot image is incorrect in basket
11) you can add quantity = 0 and proceed through checkout
