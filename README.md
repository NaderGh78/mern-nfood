Food Ordering Project (MERN Stack)
Project Description

A Food Ordering application built with MERN Stack (MongoDB, Express.js, React.js, Node.js).
The project is fully responsive and works on all devices.
Users can browse menu items, add products to cart, complete orders, and manage their profiles.
Includes an Admin Dashboard to manage the system.

---

For all other screenshots, see the full collection here:
[All screenshots](./screenshots)

---

User Features
Authentication

User registration and login.

---

Home Page

Food displayed inside a slider.

---

Main header menu includes:

Day/Night mode toggle.

Search icon (navigates to search page).

Shopping cart icon (opens sidebar when a product is added).

User menu (email, orders, wishlist, account, logout).

---

Menu Page

Shows all products with pagination (6 per page).

Filters:

Price (Low → High / High → Low).

Alphabetical (A → Z / Z → A).

By category (Pizza, Drinks, etc).

Option to switch view (Grid / List).

---

Product Card

Contains: Image, Name, Description, Old Price, New Price.

Buttons: Add to Cart – View Details – Add to Wishlist.

Discounted products show old price with strikethrough and new price.

When added:

"Add to Cart" changes to "In Cart" with a counter.

Wishlist icon changes color if added.

---

Sidebar (Cart Preview)

Opens when user adds a product to cart.

Shows product details (Image, Price, Quantity).

Remove product with an X icon.

Dynamic total price calculation.

Buttons: View Cart – Checkout.

---

Product Details Page

Displays: Name, Description, Price (old & new), Rating, Reviews count.

Shows category, Add to Cart, and Wishlist buttons.

Tabs: Description – Product Rating.

Related products in a slider.

Confirmation message appears when product is added to cart.

---

Cart Page

Table with product details, price, and quantity (editable).

Right section shows: Cart Total, Subtotal, Clear Cart button, Proceed to Checkout button.

---

Checkout Page

Two sections:

User info (address, city, phone, payment method: Cash on Delivery).

Order summary (products, prices, subtotal, shipping).

---

Confirm Order Page

Shows: Thank You image, Order ID, Order Date, Billing Address, Payment Method.

Buttons: Continue Shopping – Home Page – Profile.

---

Profile Page

Tabs:

User Orders

Wishlist

Account Info (name, address, contact)

Change Password

---

Admin Features

Full access to the system.

Manage Users (Add, Edit, Delete).

Manage Products (Add, Edit, Delete).

Manage Categories (Add, Edit, Delete).

Manage Orders (Change status: Pending, Processing, Completed).

---

Tech Stack

Frontend: React.js, Redux

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT

Storage: Cloudinary (for images) 