# 🛍️ NxtTrendz – React E-Commerce App

NxtTrendz is a modern e-commerce web app built with **React.js**.  
It allows users to browse products, search, filter, add to cart, and manage orders — providing a full shopping experience with authentication and responsive UI.

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

nxtTrendzCartFeatures-solution/
├── public/
├── src/
│   ├── components/
│   │   ├── AllProductsSection/      # Main products listing with filters
│   │   ├── Cart/                    # Cart page component
│   │   ├── CartItem/               # Individual cart item
│   │   ├── CartListView/           # List of cart items
│   │   ├── CartSummary/            # Order summary and checkout
│   │   ├── EmptyCartView/          # Empty cart state
│   │   ├── FiltersGroup/           # Search, category, and rating filters
│   │   ├── Header/                 # Navigation header with cart badge
│   │   ├── Home/                   # Landing page
│   │   ├── LoginForm/              # User authentication
│   │   ├── NotFound/               # 404 error page
│   │   ├── PrimeDealsSection/      # Exclusive deals section
│   │   ├── ProductCard/            # Product card component
│   │   ├── ProductItemDetails/     # Product detail page
│   │   ├── Products/               # Products page container
│   │   ├── ProductsHeader/         # Products page header with sort
│   │   ├── ProtectedRoute/         # Route protection HOC
│   │   └── SimilarProductItem/     # Similar products display
│   ├── context/
│   │   └── CartContext.js          # Global cart state management
│   ├── App.js                      # Main app component with routes
│   ├── App.css                     # Global styles
│   ├── index.js                    # App entry point
│   └── setupTests.js               # Testing configuration
└── package.json

## Steps to Run Locally

### 1. Clone the repository

```
git clone https://github.com/your-username/nxttrendz.git
cd nxttrendz
```


