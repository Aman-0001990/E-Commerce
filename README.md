# 🛒 Ecommerce Follow Along

## 🚀 E-Commerce Project - Key Takeaways

### 🎯 Project Goals
✅ Build a full-fledged e-commerce app using the MERN stack.  
✅ Gain hands-on experience in real-world full-stack development.  

---

## 📚 Learning Outcomes
📌 Understand the structure of a MERN stack project.  
📌 Set up project repositories and foundational tools.  
📌 Master core functionalities:
- 🔑 User Authentication (Login/Register).  
- 📦 Product & Order Management.  
- 🗃️ Database Schema Design.  

---

## 🛠️ Core Concepts
- 🔹 **REST API Design** → Create endpoints for users, products & orders.  
- 🔹 **MongoDB Schema** → Structure meaningful data models.  
- 🔹 **Authentication** → Secure login & registration systems.  
- 🔹 **Backend Development** → Use Node.js + Express for APIs.  

---

## 🏆 Milestones Overview

### 📌 Project Overview
🚀 Introduction to MERN stack.  
🔍 Live Demo of the final app.  
📌 Set up GitHub repo + README 📜.  

---

## 🛠️ Development Environment Setup
✅ Install tools: **Node.js, npm, MongoDB, VS Code**.  
✅ Initialize the project:
```sh
npm init
```
✅ Install dependencies:
```sh
npm install express mongoose dotenv
```

---

## ⚙️ Backend Development
🛠️ Create REST APIs for:
- 👤 **User Authentication** (Register/Login).  
- 🛍️ **Product Management** (CRUD operations).  
- 📦 **Order Handling** (Orders & Transactions).  

📌 **Database Design:**
- 🏛️ **MongoDB Schemas** for Users, Products, Orders.  
- 🛡️ Implement **middleware** for validation & error handling.  

---

## 🎨 Frontend Development
🖥️ Set up **React project** with `create-react-app` or `Vite`.  
🎨 Build **key UI components**:
- 🔑 **User Pages** (Login, Register, Profile).  
- 🛒 **Product Pages** (Listings, Search, Details).  
- 🛍️ **Order Pages** (Cart, Checkout, History).  
🔀 Use **React Router** for navigation.  
📦 Manage **state** with Redux or Context API.  

---

## 🔗 Integration, Testing & Deployment
🔗 Integrate **Frontend & Backend** using API calls.  
🛠️ Test with **Postman** and fix bugs 🐞.  
🚀 **Deploy** the project:
- 🔥 **Backend** → Heroku, Render, or AWS.  
- 🌐 **Frontend** → Netlify or Vercel.  
🛡️ Ensure **security & performance** before launch!  

---

## 🎯 Final Deliverable
✅ A **fully functional MERN-based** e-commerce app featuring:
- 🔒 **Secure Authentication**.  
- 📦 **Product & Order Management**.  
- 📱 **Responsive & User-Friendly UI**.  
✅ Fully **tested** & **deployed online**! 🚀  

---

🔥 **Let’s build something awesome together!** 💻⚡  

# Milestone 2: Project Structure & Login Page 🚀  

## Overview  
In Milestone 2, we focused on structuring the project, setting up both the frontend and backend, and developing the Login Page for the e-commerce application.  

## Key Accomplishments  

### 📁 Project Structure  
- Organized the project with separate frontend/ and backend/ directories.  

### 🌐 Frontend Setup  
- Initialized a React app for building the user interface.  
- Configured *Tailwind CSS* for utility-based styling.  
- Implemented a fully functional and styled *Login Page*.  

### 🛠 Backend Setup  
- Set up a basic *Node.js + Express* server to prepare for future API integration.  

### 🎯 Learning Outcomes  
By completing this milestone, we learned:  
- How to structure a full-stack project.  
- Setting up a React application with Tailwind CSS.  
- Configuring a Node.js backend.  
- Creating a login page with basic styling and functionality.  

## ✅ Submission Details  
- Code is pushed to the *GitHub repository* created in Milestone 1.  
- The repository includes:  
  - *Proper folder structure* (frontend & backend).  
  - *Functional Login Page*.  
  - *Updated README* summarizing the progress.  

🚀 Ready for the next milestone


# Milestone 3: Project Setup for Backend

In this milestone, we successfully set up the backend for our Ecommerce project using Node.js, Express.js, and MongoDB.

✅ Achievements in this Milestone
Set up a Node.js backend server using Express.
Configured the server to listen on a designated port.
Integrated MongoDB for efficient data storage.
Established a connection between the server and MongoDB to confirm successful integration.


# Milestone 4: Creating User Model and Controller

### Achievements
1. **User Model:**
   - Created a User schema using **Mongoose**.
   - Defined fields such as `name`, `email`, `password`, and `profileImage`.
   - Implemented password hashing using **bcryptjs** for security.

2. **User Controller:**
   - Developed controller functions for user-related actions:
     - Registering a new user.
     - Retrieving user information.
     - Handling user authentication.
   - Integrated the controller with **Express routes**.

3. **Multer Integration:**
   - Configured **Multer** for handling file uploads.
   - Allowed users to upload profile images and store them in a designated folder.
 milestone_6
 milestone_5
   - milestone_4
main
 main


# Milestone 5: Frontend Development - Sign-Up Page

### Overview  
In this milestone, I built the **Sign-Up Page** using **HTML** and **CSS** and added **form validation** to ensure users input valid data.  

### Features  
- **Sign-Up Page**: Created a responsive and user-friendly sign-up form.  
- **Form Validation**: Added validation for required fields, email format, password matching, and minimum password length.  
 milestone_6

milestone_5
 main

# Milestone 6 - User Authentication & Encryption

In this milestone, I implemented user authentication with password encryption and saved complete user data in the database.

## Features Implemented

### 1. Encrypt the Password
- Used `bcrypt` to hash the user's password during the signup process.
- Ensured that the hashed password is saved in the database instead of storing the plain text password.

### 2. Store Complete User Data
- Saved all the user's data (e.g., name, email, etc.) into the database.
- Ensured that the password is stored securely and not in plain text.

## How It Works

- During the signup process, the user's password is hashed using `bcrypt`.
- The hashed password is then stored in the database along with other user details like name and email.
- When the user logs in, the password provided is compared with the hashed password in the database for authentication.

This ensures that sensitive user data, especially the password, is stored securely. milestone_6

main 



# Milestone 7 Completion Summary
I have successfully completed Milestone 7 by implementing the Login Endpoint with proper authentication mechanisms. Below is a step-by-step breakdown of the tasks I accomplished:

✅ 1. Created the Login Endpoint:
Implemented an API endpoint to accept user credentials (email/username and password).
Retrieved the corresponding user details from the database based on the provided email/username.
✅ 2. Validated the Password:
Used bcrypt to hash the entered password.
Compared the entered password's hash with the stored hashed password for authentication.
✅ 3. Ensured Secure Authentication:
Followed best security practices, ensuring passwords are never stored in plain text.
Used hashing for password validation instead of decryption, as password hashing is a one-way process.
With this, Milestone 7 is successfully completed 🎯.

# Milestone 8: Product Card Component and Homepage Layout 🚀
✅ Frontend Product Card Component
Designed and implemented a reusable Product Card component.
Utilized props to dynamically render product details like name, image, and price.
✅ Homepage Layout for Products
Created a responsive homepage to display multiple Product Cards.
Used Grid/Flexbox for optimal layout and user experience.


## Milestone 9: Product Input Form 🚀

### ✅ *Product Form Implementation*
- Designed a form for adding product details such as name, price, and description.
- Implemented an option for uploading multiple product images.

### ✅ *Database Integration*
- Structured the form to send product data to the backend for storage in MongoDB.
- Ensured proper validation and error handling.

### ✅ *README Update*
- Documented Milestone 9 progress in this README file.

This milestone focused on enabling product input, which is essential for expanding the e-commerce platform by allowing users to add new products dynamically.


## Milestone 10: Product Schema and API Endpoint 🚀
✅ Product Schema Implementation
Defined a Product Schema in Mongoose.
Implemented validation for fields like name, price, and image URL.
✅ API Endpoint for Adding Products
Created a POST endpoint to store product details in MongoDB.
Ensured proper validation before saving the data.

## Milestone 11: Dynamic Product Display 🚀
✅ Fetching Product Data
Created an endpoint to retrieve all stored products from MongoDB.
Implemented API call logic in the frontend to fetch data dynamically.
✅ Displaying Products
Passed fetched product data to the Product Card component.
Rendered product information dynamically on the homepage.


## Milestone 12: My Products Page 🚀
✅ Filtering Products by User Email
Created a backend endpoint to retrieve products associated with the logged-in user's email.
Queried the MongoDB database to fetch only those products matching the user's email.
✅ Fetching Data on the Frontend
Implemented an API call to request user-specific product data from the backend.
Stored the retrieved data in the application state for dynamic rendering.
✅ Displaying User's Products
Passed the fetched data to the Product Card component.
Rendered the products dynamically on the "My Products" page.

### Milestone 13: Editing Uploaded Products 🚀
✅ Backend Update Endpoint

Created an endpoint to receive and update product details in MongoDB.
Implemented logic to find the product by its ID and modify the existing data.
✅ Frontend Edit Button

Added an Edit button to each product card.
When clicked, it fetches the product details and auto-fills the form.
✅ Updating Product Data

Allowed users to modify product details directly within the form.
Implemented a Save Changes feature to update product details in the database.

## Milestone 14: Deleting Products 🚀
✅ Backend Delete Endpoint

Created an endpoint to delete a product by its ID from MongoDB.
Implemented logic to find the product and remove it from the database.
✅ Frontend Delete Button

Added a Delete button to each product card.
When clicked, it sends the product ID to the server endpoint for deletion.
✅ Updating UI After Deletion

Ensured the product is removed from the frontend dynamically after successful deletion.
Implemented confirmation prompts before deletion for better user experience.

## Milestone 15: Navbar Component 🚀
✅ Creating the Navbar Component

Designed a Nav component with links to key pages:
Home
My Products
Add Product
Cart
✅ Making the Navbar Responsive

Ensured the Navbar adapts to all screen sizes.
Implemented a mobile-friendly design with a collapsible menu.
✅ Reusing the Navbar Across Pages

Added the Nav component to all application pages.
Ensured smooth and intuitive navigation between different sections.

## Milestone 16: Product Info Page 🚀
✅ Creating the Product Info Page

Designed a Product Info page to display detailed product information.
✅ Adding Quantity Selection and Cart Button

Implemented a Quantity Selector to allow users to choose the desired quantity.
Added an Add to Cart button to facilitate easy product purchase.
✅ Dynamic Data Rendering

Integrated backend API calls to fetch and display product details dynamically.


## Milestone 17: Adding Products to Cart
✅ Updating User Schema
Modified the User Schema to include a cart field for storing added products.
✅ Cart Schema Implementation
Created a Cart Schema in Mongoose to store cart product details.
✅ Backend Cart Endpoint
Developed an API endpoint to receive product details and store them in the cart collection in MongoDB.
✅ API Integration
Ensured that product details are properly received from the frontend and stored in the cart.
✅ Testing and Validation
Implemented input validation to ensure correct product details are stored.
Tested API responses to confirm successful cart storage.


## Milestone 18: Fetching Cart Products
✅ Backend Cart Retrieval Endpoint
Created an endpoint to fetch all products inside a user's cart.
✅ User-Based Filtering
Implemented logic to retrieve cart products based on the logged-in user's email.
✅ API Integration with Frontend
Integrated the frontend cart page with the backend to fetch and display cart items.
✅ Testing and Validation
Ensured that the cart data retrieval process is working correctly.
Tested API responses for accuracy and efficiency.


## Milestone 19: Cart Page UI & Quantity Management
✅ Frontend Cart Page
Created a dedicated Cart Page UI to display products inside the cart.
Integrated the frontend with the backend endpoint from Milestone 18 to fetch cart items.
✅ Quantity Management
Implemented + (increase) and - (decrease) buttons for each cart product.
Users can modify product quantities dynamically.
✅ Backend Endpoints for Quantity Update
Created API endpoints to handle incrementing and decrementing the product quantity inside the cart.
Integrated these endpoints with the frontend.
✅ Testing and Validation
Ensured smooth UI interaction for increasing and decreasing quantities.
Tested API responses to validate quantity updates.

# Milestone 20: User Profile Page 🚀
## ✅ Backend & API Integration

Created an endpoint to send user profile data (photo, name, email, and address).
Implemented authentication and error handling for secure access.
Integrated the frontend to fetch and display user details dynamically.
✅ Frontend Profile Page

Designed a Profile Page displaying profile photo, name, and email.
Added an Address Section with an "Add Address" button.
Displayed "No address found" if no address is available.
Ensured smooth UI updates when adding an address. 🚀


##  Milestone 21: Address Form Functionality
Created an address form capturing user details (country, city, zip code, etc.).
Integrated navigation from the profile page to the address form.cd


##  Milestone 22: Address Storage Functionality
Developed a backend API endpoint to store user addresses.
Integrated the address form with the backend.

# Milestone 23: Address Selection for Orders 🛒
✅ Cart Page Enhancement

Added a "Place Order" button inside the cart page.
Navigated to the "Select Address" page when clicked.
✅ Address Selection Page

Displayed all available addresses of the user.
Provided an option to select one address for the order.
✅ Backend API Implementation

Created an endpoint to fetch and send all saved addresses of the user.

Ensured authentication and proper error handling.


# Milestone 24: Order Summary Page 🛍️

# milestone-24

Milestone 24: Order Summary Page 🛍️

✅ Display Ordered Products

Listed all products the user is ordering.
✅ Address Confirmation

Displayed the selected delivery address.
✅ Cart Value Calculation

Showed the total value of the cart.
✅ Place Order Button


Added a "Place Order" button at the bottom for final confirmation.



# Milestone 25: Order Processing Backend ⚙️
✅ Order API Implementation

Created an endpoint to receive products, user, and address details.
Retrieved the _id of the user using their email.
✅ Order Storage

Stored each product as a separate order with the same address.
Used the existing Order schema to save order details in MongoDB.



# Milestone 26: Fetch User Orders API 📦
✅ Order Retrieval Endpoint

Created an endpoint to receive the user’s email.
Retrieved the _id of the user using their email.
✅ Fetch & Response

Used the _id to fetch all orders of the user from the database.
Sent all user orders in the API response.


# Milestone 27: My Orders Page 🛍️


#Milestone 27: My Orders Page 🛍️
✅ My Orders Page

Created a "My Orders" page to display all user orders.
✅ API Integration

Sent a GET request to the my-orders endpoint.
Passed the user's email to fetch all orders.
✅ UI & Navigation

Displayed all user orders on the page.
Added "My Orders" to the navbar for easy access.



# Milestone 28: Order Cancellation Feature
✅ My Orders Page

Added a Cancel Order button for active orders.
Hidden the button for canceled orders.
✅ API Implementation

Created an endpoint to cancel orders.
Updated order status to canceled in the database.
✅ UI Integration

Sent API request on button click.
Updated UI after successful cancellation.


# Milestone 29: PayPal Integration for Online Payments 💳
✅ PayPal Developer Setup

Created a PayPal Developer account.
Accessed the PayPal Developer Dashboard.
Created a Sandbox account for testing transactions.
Copied and saved the Sandbox UserID for future reference.
Retrieved and stored the Client ID from the Sandbox account.
✅ Payment Options on Order Confirmation Page

Added two payment options: Cash on Delivery (COD) and Online Payment.
Implemented radio buttons to allow users to select their preferred payment method.
When "Online Payment" is selected, PayPal buttons will be displayed dynamically.


# # Milestone 30: PayPal Integration 💳
✅ PayPal Account Setup

Created a PayPal Developer account and a Sandbox account.
Retrieved and stored the Client ID.
✅ Implementation

Installed react-paypal-js.
Used PayPalScriptProvider to integrate PayPal payment options.
✅ Testing

Verified transactions using the Sandbox environment.


Added a "Place Order" button at the bottom for final confirmation.

# milestone 31: JWT Auth & Member CRUD 🔐
✅ JWT Authentication

Implemented secure login and signup using JWT tokens.
Stored token in localStorage and protected member routes with auth middleware.
✅ Member CRUD + UI Enhancements

Added full Create, Read, Update, Delete features for gym members.
Enhanced UI with field icons, top banner, and improved layout for better experience.

