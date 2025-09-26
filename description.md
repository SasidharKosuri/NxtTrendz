# 📝 Project Description – NxtTrendz

NxtTrendz is a **modern e-commerce web application built with React.js** that provides a complete shopping experience — from secure login to browsing products, filtering, adding to cart, and checking out. The application mirrors real-world e-commerce workflows while focusing on clean UI, performance, and responsiveness.  
It demonstrates how multiple moving parts — **authentication, product management, cart system, state management, routing, and responsive UI** — can come together into a seamless web app.

---

## 🛒 End-to-End User Flow

1. **Authentication System**
   - Users start at a **Login Page** where credentials are verified against authentication APIs.
   - JWT tokens are issued upon successful login and stored in cookies for session persistence.
   - Protected routes enforce access control — preventing unauthorized access to products and cart pages.
   - Logout functionality clears authentication cookies and redirects back to login.

2. **Browsing Products**
   - After login, users land on the **Products Page**.
   - Products are displayed in a responsive grid with name, price, rating, and product image.
   - A **Prime Deals Section** highlights exclusive offers available to all logged-in users.

3. **Search, Filter, and Sort**
   - **Search Bar:** Allows keyword-based product lookup in real time.
   - **Filters:**
     - Category filters (Clothing, Electronics, Appliances, Grocery, Toys).
     - Rating filters (1 star and above, 2 stars and above, etc.).
   - **Sorting Options:**
     - Price: Low → High.
     - Price: High → Low.
   - Filters and sorting can be combined to refine results further.

4. **Product Details Page**
   - Each product links to a detailed view.
   - Includes specifications, description, pricing, and availability.
   - **Similar Products** are displayed for product discovery and upselling.

5. **Cart System**
   - Items can be added from both product cards and product detail pages.
   - Cart allows:
     - Incrementing or decrementing item quantities.
     - Removing individual items.
     - Clearing the entire cart with a single action.
   - A **Cart Summary Section** shows:
     - Number of items.
     - Order total price.
   - If the cart is empty, an **Empty Cart View** provides a call-to-action to continue shopping.

6. **Responsive User Experience**
   - Designed with a **mobile-first approach**.
   - Layouts adjust dynamically for desktops, tablets, and mobile devices.
   - Navigation is simplified on smaller screens with collapsible menus and touch-friendly interactions.
   - Media queries and Flexbox ensure a consistent look and feel.

---

### 📚 Technical Highlights

- Component-Based Architecture ensures reusability and scalability.
- React Context API provides global state management for cart and authentication.
- ProtectedRoute Wrapper implements access control based on authentication.
- API Integration handles product listings, details, authentication, and Prime Deals.
- Async Handling: Loader spinners and error boundaries for better UX.
- Responsive Design: Mobile-first layout using Flexbox and media queries.

🧰 Tech Stack

- Languages: JavaScript (ES6+), JSX, CSS3
- Framework: React.js
- Routing: React Router DOM
- State Management: Context API + React Hooks
- Authentication: JWT with Cookies
- UI Tools: React Icons, React Loader Spinner
- Build Tool: Create React App
