# Razorpay Clone

Welcome to the **Razorpay Clone** project! This repository showcases a full-stack implementation of a payment gateway system inspired by Razorpay. The project replicates essential payment gateway features with a user-friendly interface and robust backend functionality. Vibrant charts and diagrams highlight the key features and workflows. Dive in to explore this modern payment system!

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)
- [Frontend Highlights](#frontend-highlights)
- [Backend Highlights](#backend-highlights)
- [Database Design](#database-design)
- [Visualizations](#visualizations)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Razorpay Clone project is a simulation of a modern payment gateway system that supports secure transactions, payment tracking, and user management. It provides a seamless experience for businesses and customers alike. This project was developed to understand the complexities of payment systems and to showcase scalable application design.

## Features
- **User Authentication**: Secure login and registration system.
- **Payment Integration**: Mock payment processing for cards, UPI, and wallets.
- **Transaction Management**: Track and manage payment statuses in real-time.
- **Dashboard**: Interactive dashboard for merchants to view transaction insights.
- **Webhooks**: Simulated webhooks for real-time updates.

## Technologies Used
- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **API Testing**: Postman
- **Charts**: Chart.js
- **Authentication**: JWT (JSON Web Tokens)

## Architecture
The project follows a **Model-View-Controller (MVC)** architecture to ensure scalability and maintainability.

![Architecture Diagram](images/architecture.png)

## Frontend Highlights
- **Responsive Design**: Built with Tailwind CSS for a seamless user experience across devices.
- **Payment UI**: Intuitive forms and modals for payment details.
- **Dashboard**: Dynamic charts and transaction tables.

## Backend Highlights
- **RESTful APIs**: Built with Express.js for handling requests.
- **Secure Transactions**: Implements encryption for sensitive data.
- **Webhooks**: Simulates notification handling for payment statuses.

## Database Design
The database is structured for optimal performance and scalability:
- **Users**: Stores user credentials and profiles.
- **Transactions**: Records payment details, statuses, and timestamps.
- **Webhooks**: Tracks webhook events for debugging.

![Database Schema](images/database_schema.png)

## Visualizations
We used Chart.js to create engaging charts and graphs:
- **Revenue Trends**: Line chart showing daily revenue growth.
- **Payment Methods**: Pie chart displaying the distribution of payment methods.
- **Transaction Volume**: Bar chart highlighting transaction counts per hour.

![Revenue Trends](images/revenue_trends.png)
![Payment Methods](images/payment_methods.png)
![Transaction Volume](images/transaction_volume.png)

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/riteshravi1002@gmail.com/razorpay-clone.git
   ```
2. Install dependencies:
   ```bash
   cd razorpay-clone
   npm install
   ```
3. Configure environment variables in `.env` file.
4. Start the development server:
   ```bash
   npm start
   ```
5. Access the app at `http://localhost:3000`.

## Contributing
We welcome contributions! Please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

