# Rentify - Where Renting Meets Simplicity

# Overview
Rentify is a real estate application designed to simplify the process of renting properties by connecting property owners (sellers) and potential tenants (buyers). This application allows sellers to list their properties and manage them, while buyers can search for properties, express interest, and get in touch with sellers.

# Tech Stack
Frontend: React
Backend: Node.js
Database: MySQL

# Features
# Part I: Basic Application
User Authentication
Registration (First Name, Last Name, Email, Phone Number)
Login
Seller Flow
Post Property: Details include place, area, number of bedrooms, bathrooms, nearby hospitals & colleges, etc.
View Properties: Sellers can see a list of properties they have posted.
Update/Delete Properties: Sellers can update or delete their properties.
Buyer Flow
View Properties: Buyers can view all posted rental properties.
Express Interest: Buyers can click an "I'm Interested" button to view seller details.
Apply Filters: Buyers can filter properties based on property details.
# Part II: Advanced Features
Pagination: Implement pagination for property listings.
Form Validation: Ensure proper validation for all forms.
Protected Routes: Mandate login for buyers to view seller details and redirect unauthorized users to the login screen.
Like Button: Add a like button to each property and track the count live.
Email Notifications:
Send seller’s contact details to the buyer via email when the "I'm Interested" button is clicked.
Notify the seller via email with details of the interested buyer.
# Part III: Bonus 
Deployed the application on a cloud platform withe help of
vercel andd clever cloud
webiste link: https://frontend-virid-one-37.vercel.app/

#  Installation and Setup
Backend (Node.js)
1. Navigate to Backend Directory
cd rentify/backend
2. Install Dependencies
npm install
3. Database Setup
Create a MySQL database named rentify.
Configure the database connection in config/db.js.
Run Server
npm start
The backend server will start on http://localhost:5000

# Frontend (React)
1. Navigate to Frontend Directory
cd rentify/frontend
2. Install Dependencies
npm install
3. Run Application
npm start
The frontend application will start on http://localhost:3000

# API Endpoints
Authentication
POST /register: Register a new user.
POST /login: Authenticate a user and get a token.
Properties
POST /postproperties: Create a new property (Seller only).
GET /properties: Get all properties.
GET /properties/:id: Get a single property.
PUT /properties/:id: Update a property (Seller only).
DELETE /properties/:id: Delete a property (Seller only).
Interest
POST /properties/:id/interest: Express interest in a property (Buyer only).

# Deployment
Cloud Platform
Vercel
Clever cloud

# Conclusion
Rentify is designed to streamline the rental process by providing a user-friendly platform for property owners and tenants. The application is scalable, secure, and can be enhanced with additional features as required.
