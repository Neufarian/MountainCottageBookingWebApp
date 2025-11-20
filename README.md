# 🏔️ Mountain Cottage – Full-Stack Web App

A full-stack web platform for renting mountain cottages in Serbia, built with Angular, Node.js (Express), and MongoDB.
The application supports multiple user roles, offers a full booking workflow, provides dynamic map interactions, and includes cottage management tools for owners and administrators.

## ✨ Key Features
🔐 Multi-Role Authentication

- Three user types: Tourist, Owner, Administrator
- Login & registration with form validation
- Protected routes and role-based UI

🏡 Cottage Management

- Cottage listing with images, descriptions, and amenities
- Advanced search & filtering (location, name)
- Sorting options (location, name)
- Detail pages with image galleries and map location

📅 Booking System

- Multi-step booking form
- Availability validation
- Automatic price calculation
- Owners receive booking requests in real time

🗺️ Dynamic Map Integration

👤 User Profiles

- Profile editing (name, email, images)
- Booking history
- For owners: cottage uploads, photo uploads, availability configuration
- For admins: user and listing moderation

📊 Owner Dashboard

- Calendar with incoming booking requests
- Approve / decline bookings
- Manage cottage availability
- Upload new cottages with images and metadata

📱 Responsive UI

- Desktop, tablet, and mobile friendly
- Optimized Angular component structure
- Clear and clean navigation

## 🛠️ Tech Stack

Frontend

- Angular
- HTML, CSS
- TypeScript
- Angular Router & Services
- Reactive Forms

Backend
- Node.js
- Express.js
- File upload support
- Error-handling middleware

Database
- MongoDB
- Mongoose ODM
- Collections: Users, Cottages, Reservations

Development Tools
- VS Code
- Postman (API testing)
- MongoDB Compass

## 📝 Notes

- This project was built as part of a university full-stack course.
- Supports modular feature expansion (reviews, payments, notifications).
- Designed following clean architecture principles and component reusability.
  
