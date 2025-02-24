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