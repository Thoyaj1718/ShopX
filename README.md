# ShopX – E‑Commerce Application 🛒

ShopX is a React‑based e‑commerce web app inspired by Nxt Trendz projects.  
It includes authentication, protected routes, products, cart management, and a payment popup with Cash on Delivery.

## ✨ Features

- Secure login using JWT authentication
- Protected routes for Home, Products, Product Details, and Cart
- Products listing with details like image, brand, price, and rating
- Specific Product Details page with quantity control and Add to Cart
- Cart with:
  - Add / remove items
  - Increment / decrement quantity
  - Live total amount and total items
  - Remove single item or clear all
- Payment popup on Checkout:
  - Payment options: Card, Net Banking, UPI, Wallet, Cash on Delivery
  - Only *Cash on Delivery* enabled, others disabled
  - Order summary (items count + total amount)
  - “Confirm Order” button enabled only when COD is selected
  - Success message: “Your order has been placed successfully”

## 🧰 Tech Stack

- React 18
- React Router DOM
- Context API for Cart state
- js-cookie for JWT handling
- React Icons for UI controls
- CSS for styling

## 🚀 Setup Instructions



git clone https://github.com/Thoyaj1718/ShopX.git
cd ShopXinstall dependenciesnpm installstart development servernpm start


The app runs at http://localhost:3000.

## 🔐 Test Credentials

Prime user:

- username: rahul  
- password: rahul@2021

(These credentials are provided by the NxtWave/Nxt Trendz API specification.)

## 📁 Project Structure

- src/
  - App.js – route configuration
  - components/
    - Login/
    - Home/
    - Products/
    - ProductItemDetails/
    - Cart/
    - CartItem/
    - CartSummary/
    - ProtectedRoute/
    - PaymentPopup/ (ShopX enhancement)
  - context/CartContext.js – global cart state and actions
- public/ – static assets and base HTML
- package.json – scripts and dependencies

## ✅ What I Implemented / Learned

- Implemented full cart logic without duplicates (same product updates quantity).
- Updated cart summary and prices based on quantity changes.
- Implemented remove single item and remove all items.
- Built a payment popup with validation around Cash on Delivery.
- Worked with protected routes and JWT‑based auth in React apps.

---

Built by *Thoya J* as a personal e‑commerce project (ShopX).
