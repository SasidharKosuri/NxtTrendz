# 🛍️ NxtTrendz – React E-Commerce App

NxtTrendz is a modern React.js-based e-commerce web application that simulates a real-world shopping platform.  
It enables users to seamlessly browse through a wide catalog of products, explore exclusive deals, and access detailed product pages with descriptions, specifications, and recommendations.With search, filters, sorting, and ratings, customers can quickly discover the right products for their needs. The app also includes a secure authentication system powered by JWT tokens, ensuring that only logged-in users can access protected routes such as the shopping cart. The cart itself is fully interactive, allowing users to add, update, or remove products, view a live order summary, and even clear the entire cart in one click. Built with a mobile-first, responsive design, NxtTrendz delivers a smooth and consistent shopping experience across desktops, tablets, and mobile devices.

---

## ✨ Core Features

### 🔐 Authentication
- JWT-based login system
- Protected routes (only logged-in users can access shop/cart)
- Automatic session handling with cookies

### 🛍️ Product Catalog
- Product grid with images, prices, ratings
- Advanced filters (category, rating, search)
- Sorting options (price high→low, low→high)
- Prime Deals section (exclusive products)
- Product detail pages + similar product suggestions

### 🛒 Shopping Cart
- Add, remove, and update quantities
- View cart summary with real-time total
- “Clear All” option
- Persistent cart state during session
- Cart badge indicator in header

### 📱 UI & Responsiveness
- Mobile-first responsive design
- Works smoothly on desktop, tablet, and mobile
- Clean navigation and intuitive layout

---

## 🛠️ Tech Stack
- **React.js** – component-based UI
- **React Router DOM** – routing
- **Context API + Hooks** – global state management
- **Cookies (JWT)** – authentication
- **React Icons / Loader Spinner** – UI elements
- **CSS3 (Flexbox & Media Queries)** – styling
- **Create React App** – project setup

---

## 📂 Project Structure

<img width="723" height="580" alt="image" src="https://github.com/user-attachments/assets/f8bb7af8-764d-4302-bd1c-23e33f2a4463" />


## Steps to Run Locally

### 1. Clone the repository

```
git clone https://github.com/SasidharKosuri/nxtTrendz.git
cd nxtTrendz
```

### 2.Install dependencies

```
npm install
```

### 3.Start the development server

```
npm start
```

### 4.Open your browser

The app will automatically open at http://localhost:3000
Use demo credentials to login

<img width="1203" height="780" alt="image" src="https://github.com/user-attachments/assets/35f4ff56-28f1-4ffc-9fa8-e8ca7094b865" />

## 🔧 Key Components Overview

### 🏠 Home Component
- Welcome page with promotional content
- "Shop Now" button redirecting to products page
- Responsive design with different layouts for mobile and desktop

### 🔐 Authentication System
- LoginForm: Handles user authentication with JWT tokens
- ProtectedRoute: Higher-order component for route protection
- Automatic token validation and redirects

### 🛍️ Product Management
- AllProductsSection: Main product grid with filtering and sorting
- ProductItemDetails: Individual product pages with similar products
- PrimeDealsSection: Special offers section
- FiltersGroup: Advanced filtering by category, rating, and search

### 🛒 Cart System
- CartContext: Global state management for cart operations
- Cart: Main cart page with list view and summary
- CartItem: Individual cart item with quantity controls
- CartSummary: Order total and checkout button

### 🎨 UI Components
- Header: Navigation with cart badge and logout
- ProductCard: Reusable product display component
- SimilarProductItem: Related products display

### 🔄 State Management
- The app uses React Context API for global state management:

### CartContext Features:
- cartList: Array of cart items
- addCartItem(): Add products to cart
- removeCartItem(): Remove specific items
- incrementCartItemQuantity(): Increase item quantity
- decrementCartItemQuantity(): Decrease item quantity
- removeAllCartItems(): Clear entire cart

### 🌐 API Integration
The app integrates with a mock e-commerce API providing:
- Product listings with pagination
- Product details and similar products
- User authentication endpoints
- Prime deals exclusive offers

### 📱 Responsive Design Features
- Mobile-first CSS approach
- Flexible grid layouts using Flexbox
- Media queries for different screen sizes
- Touch-friendly buttons and controls
- Optimized images and loading states

