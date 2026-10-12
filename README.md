# FoodieFlow — HTML, CSS & JavaScript demo

FoodieFlow is a responsive, browser-based food delivery **demo MVP** built with plain HTML, CSS and JavaScript. It includes restaurant discovery, searchable menus, a cart, checkout form validation, coupon calculations, demo order confirmation/tracking, order history, demo account screens, and a local demo admin dashboard.

## Run locally
1. Download and extract `FoodieFlow.zip`.
2. Open the `FoodieFlow` folder in VS Code.
3. Open `index.html` in your browser, or use the VS Code **Live Server** extension and choose **Open with Live Server**.
4. No npm installation is required.

## Files
- `index.html` — page structure and all views
- `style.css` — responsive design and component styling
- `script.js` — sample data, navigation, search, menu/cart logic, checkout, and demo orders

## Included interactions
- Browse 10 sample restaurants with sample ratings, offers and delivery estimates.
- Search/filter restaurants and menu dishes.
- Open a restaurant menu, filter vegetarian/non-vegetarian items, and add items to the cart.
- One-restaurant-at-a-time cart, quantity changes, clear/remove, estimated tax and delivery fee.
- Coupon `FLOW10` applies a 10% discount on item subtotals of ₹399 or more.
- Checkout validates required details and phone/PIN formats.
- Cash on Delivery or clearly labelled simulated online payment (no payment is collected).
- Order confirmation, order history, simulated status progression and reorder.
- Browser-local demo profile, favourites, cart and orders.
- Local demo admin view for toggling restaurant availability and updating sample order status.

## Important limitations
This is a **front-end-only learning/demo project**. `localStorage` is used for persistence. It has no Express server, MongoDB database, secure server-side authentication, real restaurant integration, real payment gateway, real order fulfilment, email/SMS, or GPS tracking. The demo account password is stored in browser storage and is **not secure**; never use a real password. The admin screen is not protected and must not be used for production. Restaurant ratings, fees, availability, offers, delivery times and order status are sample content. Food images require an internet connection.

For a production deployment, build the Express/MongoDB backend, hash passwords with bcrypt, enforce roles server-side, calculate order totals on the server, and integrate a payment provider in test mode before enabling live payments.
