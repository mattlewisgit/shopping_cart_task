# Kingfisher Shopping Cart Demo

**Calculator available at:** [Demo Link](https://mattlewisgit.github.io/shopping_cart_task/)

---

## User Story

**Title:** Shopping Cart

**Description:**  
As a Kingfisher user, I want to add products to the basket, log in, and place an order to prove that my webpage works as expected.

---

## Acceptance Criteria

1. I can add all the available products to the basket.  
2. I can remove a single product quantity from the basket.  
3. I can apply a discount using:  
   - `SAVE10` → 10% discount  
   - `SAVE20` → 20% discount  
4. I can only checkout with the following credentials:  
   - **Username:** `user`  
   - **Password:** `pass`  
5. I receive a **"Checkout successful! Thank you for your purchase"** message.

---

## Known Bugs

1. You can add and proceed through checkout with more than the stock available.  
2. You can add discounts from 30% up to 100% (using `SAVE30`, `SAVE40`, etc.).  
3. You can checkout with an empty basket.  
4. If multiple quantities of the same product are in the basket, you cannot remove a single quantity.  
5. One product is priced in **Dollars** instead of Pounds.  
6. You cannot add more than 1 **Pepper** to the basket — attempting to add more removes it entirely.  
7. Adding **Orange** to the cart also adds a **Banana** (which may be out of stock).  
8. If the username is correct but the password is empty, checkout succeeds.  
9. **Carrot** value is £0.60, but in the basket it shows as £0.70.  
10. **Carrot** image is incorrect in the basket.  
11. You can add a quantity of `0` and proceed through checkout.  
