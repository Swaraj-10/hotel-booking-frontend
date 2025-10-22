# Hotel Booking Web Application

A full-stack **MERN** web application that allows users to **book hotels**, manage reservations, and make **secure online payments** through a responsive and intuitive interface.

## Overview

This platform enables users to:  
- Browse and filter hotels based on location, price, and amenities  
- Register and log in securely using **Clerk Authentication**  
- Book rooms in real time with instant confirmation emails  
- Pay securely using the **Stripe Payment Gateway**  
- Manage bookings (view, cancel, or rebook)  

The project demonstrates modern **full-stack development** including **frontend/backend integration**, **authentication**, **database design**, and **payment processing**.

## Tech Stack

- **Frontend:** React.js, HTML5, CSS3  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** Clerk  
- **Payment Gateway:** Stripe  
- **Tools:** Git, Postman, Docker

## Features

1. **User Authentication:** Secure sign-up and login via Clerk with email verification.  
2. **Hotel Listings:** Dynamic room availability and admin management of hotels.  
3. **Booking Management:** Real-time booking confirmation, email notifications, and booking modification/cancellation.  
4. **Payment Integration:** Stripe for secure online payments supporting multiple methods.  

## Installation & Setup

1. Clone the repository:  
   git clone https://github.com/Swaraj-10/hotel-booking-frontend.git

2. Navigate to the project folder and install dependencies:  
   cd hotel-booking-frontend  
   npm install

3. Set up environment variables:  
   REACT_APP_CLERK_FRONTEND_API=<your-clerk-frontend-api>  
   REACT_APP_STRIPE_PUBLIC_KEY=<your-stripe-public-key>

4. Start the application:  
   npm start

5. Access the app at: http://localhost:3000

## Project Structure

hotel-booking-frontend/  
├── public/  
├── src/  
│   ├── components/      # Reusable React components  
│   ├── pages/           # Different pages (Home, Booking, Admin)  
│   ├── services/        # API calls and integrations  
│   ├── styles/          # CSS files  
│   └── App.js           # Main React component  
└── package.json

## Demo & Repository

The application source code is available on GitHub:  
[Hotel Booking Web App](https://github.com/Swaraj-10/hotel-booking-frontend)
