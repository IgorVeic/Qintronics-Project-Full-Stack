# 💻 Qintronics Electronics Store - Full-Stack

Qintronics is a comprehensive full-stack e-commerce application built to provide a seamless shopping experience for electronics. It features robust functionalities for customers, admins, and delivery personnel, ensuring an efficient and scalable solution.

# 🖥️ Technologies Used

**Frontend:**

- **React:** Component-based user interface.
- **Tailwind CSS:** For modern and responsive styling.
- **Framer Motion:** For animations.
- **TypeScript:** Ensures type safety.

**Backend:**

- **Node.js:** Server-side runtime.
- **NestJS:** Framework for scalable backend architecture.
- **TypeORM:** ORM for database interactions.

**Database:**

- **PostgreSQL:** Relational database for storing application data.

**Documentation:**

- **Swagger:** API documentation.

# 📂 Project Structure

**The project is divided into two main directories:**

1. Client: Contains the frontend code.
2. Server: Contains the backend code.

**Server Folder Structure:**

- auth: Handles authentication and authorization.
- categories, sections: Manage product sections and categories.
- products: CRUD operations for products.
- orders: Manage order lifecycle.
- email: Manages email notifications.
- users, user-info: User profiles and additional information.

# 🛠️ Features

# User Roles and Permissions:

**Admin:**

- Perform CRUD operations on products, sections, and categories.
- Manage user roles (customer, admin, delivery person).
- View all registered orders.
- Cancel orders if needed.
- View analytics, including:
  - Total Sales
  - Orders
  - Customers
  - Average Order Value
- See a chart displaying orders by months in the current year.
- Delete registered user profiles.

**Delivery Person:**

- Mark orders as taken or delivered.

**Customer:**

- Make orders and pay with cash or card (save card details if needed).
- Cancel orders if they haven’t been taken.
- Receive email notifications for order registration or cancellation.
- View and edit profile information.
- Save and use delivery and payment details for future orders.

# E-Commerce Functionalities:

**Products:**

- Add products to favorites.
- Compare products.
- View products on sale with calculated discount.

**Orders:**

- Real-time status tracking.
- Order details including product list, address, quantity, and total cost.
- Notifications via email for order confirmation and cancellation.

**Gift Cards:**

- Customize and add gift cards to orders.

**Search:**

- Search bar in the navbar allows users to quickly search for products by name.
- Use an AI chatbot to search for specific products.

# Additional Features:

**Authentication:**

- User registration, login, and logout.
- Password reset functionality via email.

**Email Subscription:**

- Users can subscribe to newsletters.

**Sections and Categories:**

- Categorized browsing for products (e.g., Electronics, Gaming, Accessories).

**Contact Form:**

- Allows users to send inquiries.

# 🛒 Shopping Cart

- **Product Display**:

  - Lists all added products with images, names, and descriptions.
  - Displays the price of each product, the selected quantity, and the subtotal.

- **Quantity Management**:

  - Allows users to increase or decrease the quantity of each product in the cart using intuitive "+" and "-" buttons.
  - Automatically updates the subtotal and total amount when quantities are changed.

- **Remove Products**:

  - Users can remove individual products from the cart using the "Remove" button (❌).

- **Summary and Actions**:
  - Shows a detailed summary, including the total price of all selected items.
  - Offers two action buttons:
    - **Continue Shopping**: Navigates back to the product page for adding more items.
    - **Checkout**: Proceeds to the payment and order confirmation process.

# 📦 Database

- PostgreSQL: Includes tables for users, products, orders, categories, sections, and more.

# 📧 Email Notifications

- Users receive real-time email updates for order status and inquiries.

# 🚀 How to Run the Project

1. Clone the repository.
2. Navigate to the client and server directories and install dependencies using npm install.
3. Initialize the database with Swagger APIs:
   - **/api/users/init-users**
   - **/api/sections/backfill**
4. Start the client and server:
   - Client: **npm run dev** (React app).
   - Server: **npm run start:dev** (NestJS app).
5. Open the application in your browser.
