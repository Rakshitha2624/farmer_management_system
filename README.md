# Farm Management System

A web-based platform developed to assist farmers by providing centralized access to agricultural resources, best practices, and an online marketplace. This system connects farmers and buyers, enabling seamless sharing of data, selling of produce, and purchasing of agricultural tools and seeds.

##  Objective

To develop a digital solution that empowers farmers with:

- Access to best farming practices
- Tools to manage crop/product data
- A platform to sell their produce online
- Buyer-farmer interaction through request and email systems
- Self-service profile management

##  Technologies Used

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Python (Flask)  
- **Database**: SQLite   
- **Tools**: VS Code, GitHub, GitHub Desktop  

##  Features

-  **Farmer Portal**: Register, login, manage profile and crop details  
-  **Marketplace**: Farmers can list their products; buyers can browse and send purchase requests  
-  **Tool/Seed Store**: Farmers can order tools and seeds directly from sellers  
-  **Request System**: Buyers can send requests via email for product inspection  
-  **User Management**: Secure login with session tracking  
-  **Edit/Delete Options**: Farmers can edit or delete their profile and product entries  
  

## Modules Overview

### Farmer Functions:
- Register/Login
- Add/Edit/Delete profile info
- Add new crops/products
- View buyer requests

### Buyer Functions:
- View listed products
- Send purchase requests via mail
- Contact farmers via platform

## Database Design

- User Table (Farmer, Buyer credentials)
- Product Table (Crop details, availability)
- Purchase Request Table (request details)
- Tools/Seeds Table (optional for expansion)
