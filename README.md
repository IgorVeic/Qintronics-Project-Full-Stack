# 💻 Qintronics Electronics Store - Full-Stack

Qintronics is a comprehensive full-stack e-commerce application built to provide a seamless shopping experience for electronics. It features robust functionalities for customers, admins, and delivery personnel, ensuring an efficient and scalable solution.

# 🖥️ Technologies Used

Frontend:
- React: Component-based user interface.
- Tailwind CSS: For modern and responsive styling.
- Framer Motion: For animations.
- TypeScript: Ensures type safety.

Backend:
• Node.js: Server-side runtime.
• NestJS: Framework for scalable backend architecture.
• TypeORM: ORM for database interactions.

Database:
• PostgreSQL: Relational database for storing application data.

Documentation:
• Swagger: API documentation.

# 📂 Project Structure

The project is divided into two main directories:

1. Client: Contains the frontend code.
2. Server: Contains the backend code.

Server Folder Structure
• auth: Handles authentication and authorization.
• categories, sections: Manage product sections and categories.
• products: CRUD operations for products.
• orders: Manage order lifecycle.
• email: Manages email notifications.
• users, user-info: User profiles and additional information.

# 🛠️ Features

# User Roles and Permissions:

Admin:
• Perform CRUD operations on products, sections, and categories.
• Manage roles (customer, admin, delivery person).
• View all registered orders.

Delivery Person:
• Mark orders as taken or delivered..

Customer:
• Make orders and pay with cash or card (save card details if needed).
• Cancel orders if they haven’t been taken.
• Receive email notifications for order registration or cancellation.
• View and edit profile information.
• Save and use delivery and payment details for future orders.

# E-Commerce Functionalities:

Products:
• Add products to favorites.
• Compare products.
• View calculated discounts.

Orders:
• Real-time status tracking.
• Order details including product list, address, quantity, and total cost.
• Notifications via email for order confirmation and cancellation.

Gift Cards:
• Customize and add gift cards to orders.

Search:
• Use an AI chatbot to search for specific products.

# Additional Features:

Authentication:
• User registration, login, and logout.
• Password reset functionality via email.

Email Subscription:
• Users can subscribe to newsletters.

Sections and Categories:
• Categorized browsing for products (e.g., Electronics, Gaming, Accessories).

Contact Form:
• Allows users to send inquiries.

# 📜 API Usage

Initial Setup:

1. Initialize users via /api/users/init-users.
2. Backfill sections via /api/sections/backfill.

Auth Endpoints:
• /api/auth/register: Register a user.
• /api/auth/login: Log in.
• /api/auth/logout: Log out.
• /api/auth/forgot-password: Send a password reset email.
• /api/auth/reset-password: Save a new password.

Additional Endpoints:
• /api/products: Manage products.
• /api/orders: Manage orders.

# 📦 Database

• PostgreSQL: Includes tables for users, products, orders, categories, sections, and more.

# 📧 Email Notifications

• Users receive real-time email updates for order status and inquiries.

# 🛠️ How to Run the Project

1. Clone the repository.
2. Navigate to the client and server directories and install dependencies using npm install.
3. Start the client and server:
   • Client: npm start (React app).
   • Server: npm run start (NestJS app).
4. Initialize the database with Swagger APIs:
   • /api/users/init-users
   • /api/sections/backfill
5. Open the application in your browser.

# 🌟 Features Overview:

• Over 500+ products managed via backend.
• Card payment with optional saved card details.
• Interactive and responsive UI for all devices.
• Role-based functionality for Admin, Delivery Person, and Customers.
