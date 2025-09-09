# Kingfisher Shopping Cart Demo

URL: https://mattlewisgit.github.io/shopping_cart_task/

## Overview
This is a simple web-based shopping cart demo built with HTML, CSS, and JavaScript.

It includes:

- Product catalog with **Fruits** and **Vegetables**.
- Stock tracking and out-of-stock notifications.
- Shopping cart with dynamic updates.
- Discount code support.
- Checkout process with login authentication.

---

## Features

### 1. Product Sections
- **Fruits:** Apple, Banana, Orange, Grapes, Kiwi
- **Vegetables:** Carrot, Tomato, Cucumber, Pepper, Broccoli
- Each product shows:  
  - Image  
  - Name & Price  
  - Stock count  
  - Quantity selector  
  - Add to Cart button  

> Note: Products with zero stock are marked **Out of Stock** and cannot be added to the cart.

---

### 2. Shopping Cart
- Displays selected products with quantity and line total.  
- Shows total price dynamically.  
- Allows removing items from the cart.

---

### 3. Discount Codes
- Apply discount codes to reduce total price.  
- Available discount codes:

| Code      | Discount |
|-----------|----------|
| SAVE10    | 10%      |
| SAVE20    | 20%      |
| SAVE30    | 30%      |
| SAVE40    | 40%      |
| SAVE50    | 50%      |
| SAVE60    | 60%      |
| SAVE70    | 70%      |
| SAVE80    | 80%      |
| SAVE90    | 90%      |
| SAVE100   | 100%     |

---

### 4. Checkout
- Click **Checkout** to start the checkout process.  
- A login section appears embedded in the page.  
- Enter the credentials below and click **Login & Pay**.  
- On successful login, a **Checkout Successful!** message will appear, and the cart will be cleared.

#### Login Credentials
- **Username:** `user`  
- **Password:** `pass`

> The current version only validates non-empty username/password for demonstration purposes.

---

## 5. User Story / Test Scenario

**Goal:** Test the full shopping cart workflow including products, discounts, and checkout.

**Scenario:**

1. **Open the site:**  
   - Open `index.html` in a browser.

2. **Browse products:**  
   - Click **Fruits** to expand and see products.  
   - Add 2 Apples to the cart.  
   - Attempt to add 1 Banana (should be blocked because stock = 0).  
   - Add 1 Orange and 3 Grapes.

3. **Verify cart:**  
   - Ensure items appear with correct quantities and line totals.  
   - Verify **Total** reflects added items.

4. **Apply a discount code:**  
   - Enter `SAVE20` and click **Apply**.  
   - Verify **Total** updates with a 20% discount.

5. **Checkout:**  
   - Click **Checkout**.  
   - Enter **Username:** `user` and **Password:** `pass`.  
   - Click **Login & Pay**.  
   - Confirm **Checkout Successful!** message appears.

6. **Verify empty cart:**  
   - Ensure cart is cleared and **Basket is empty** message is displayed.

7. **Optional:**  
   - Try adding more than 99 items of a product to test the 2-second simulated delay.

---

## 6. Notes
- Products with zero stock cannot be added.  
- Discount codes are case-insensitive.  
- Large quantities simulate a delay for realistic behavior.
