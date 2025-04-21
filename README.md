ShopStyle React E-Commerce App
ShopStyle is a demo e-commerce web app built with React, featuring authentication, category-based product browsing, cart management, and mobile-friendly navigation.

Features
User Authentication: Simple login system with demo accounts (no backend).

Product Catalog: Browse products by category (T-Shirts, Shirts, Lowers, Shoes).

Cart: Add to cart, view cart, remove items, and see total.

Protected Routes: Shop and Cart pages require login.

Mobile Responsive: Navigation and category filters adapt for mobile devices.

Category Placeholders: Products use clear, category-specific placeholder images.

Demo Accounts
Use these credentials to log in:

User:
Email: user@example.com
Password: password123

Admin:
Email: admin@example.com
Password: admin123

Project Structure
text
src/
  components/
    Login.jsx
    Navbar.jsx
    ProductCard.jsx
    MobileCategoryFilter.jsx
  contexts/
    AuthContext.jsx
    ProductContext.jsx
  pages/
    Shop.jsx
    Cart.jsx
  utils/
    PrivateRoute.jsx
  App.jsx
  index.js / main.jsx
  index.css
  App.css
How It Works
Login:
Users must log in to access the shop and cart. Credentials are checked against a hardcoded demo list.

Product Data:
Products are loaded with category, name, price, discount, and a relevant placeholder image.

Shop Page:
Browse all products or filter by category. Each product card shows image, description, price, discount, and "Add to Cart" button.

Cart Page:
View items in your cart, remove items, and see subtotal and total.

Navigation:
Navbar and category filters allow quick navigation. Mobile menu adapts for small screens.

State Management:
Uses React Context for authentication and product/cart state. Cart and login status are persisted in localStorage.

Running the App
Install dependencies:

text
npm install
Start the development server:

text
npm start
Open in browser:
Visit http://localhost:3000

Customization
Product Images:
Product images are static placeholders by category. To use real images, update the image field in ProductContext.jsx.

Authentication:
For real authentication, replace the logic in AuthContext.jsx with API calls to your backend.

Styling
Uses CSS files (index.css, App.css, and component-specific CSS) for layout, colors, and responsiveness.

License
This project is for educational/demo purposes only.

You can copy this content into a README.md file in your project root. Adjust as needed for your deployment or further customization.

