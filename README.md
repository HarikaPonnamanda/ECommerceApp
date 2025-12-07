# E-Commerce Web Application – ASP.NET Core MVC

## Overview
This is a full-stack E-Commerce web application developed using ASP.NET Core MVC and SQL Server. The system allows users to browse products, add items to the shopping cart, and view subtotal and total bill amounts using session-based cart logic. The application demonstrates complete CRUD operations, MVC architecture, and database integration.

## Features
- Product listing with image, name and price
- Add to Cart functionality
- Cart page with price, quantity, subtotal and total calculation
- Increase and decrease quantity for cart items
- Remove item from cart
- Session-based cart management
- Responsive Razor UI pages

## Technology Stack
- Framework: ASP.NET Core MVC
- Language: C#
- Database: SQL Server with Entity Framework Core
- Frontend: HTML, CSS, Bootstrap, Razor Views
- Tools: Visual Studio 2022, SQL Server Management Studio, Git & GitHub

## Project Highlights
- Implements MVC design pattern for clean separation of concerns
- Entity Framework Core used for database CRUD operations
- LINQ used for filtering and aggregation of cart items
- Session is used to maintain cart details per user
- Strongly typed Razor Views for dynamic UI rendering

## Project Structure
Controllers/
Models/
Views/
 ├── Products
 ├── Cart
wwwroot/
Database/

## How to Run
1. Clone the repository
2. Open the solution in Visual Studio 2022
3. Update the database connection string in appsettings.json
4. Run EF migrations or create the database manually
5. Press F5 to run the project

## Future Enhancements
- Checkout and payment module
- Admin panel for product management
- Order history and tracking
- Email notification service

## Author
Harika Ponnamanda  
