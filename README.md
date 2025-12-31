# Wanderlust Project ✈️

Wanderlust is a full-stack web application designed for travelers to discover, share, and manage travel destinations. This platform allows users to explore various locations, view detailed descriptions, and manage listings through a complete CRUD (Create, Read, Update, Delete) cycle.

## 🚀 Features

* **Destination Listings:** View a wide array of travel spots with high-quality images.
* **CRUD Operations:** Authorized users can create, edit, and delete their own listings.
* **User Reviews:** Integration for users to leave feedback and ratings on destinations.
* **Secure Authentication:** User signup and login functionality for personalized experiences.
* **Image Uploads:** Support for cloud-based image storage (e.g., Cloudinary).

## 🛠️ Tech Stack

* **Frontend:** EJS (Embedded JavaScript templates), CSS, Bootstrap
* **Backend:** Node.js, Express.js
* **Database:** MongoDB with Mongoose ODM
* **Authentication:** Passport.js
* **Storage:** Cloudinary (via `cloudConfig.js`)

## 📂 Project Structure

```text
Wanderlust-project/
├── controllers/    # Logic for handling requests
├── init/           # Database initialization scripts
├── models/         # Mongoose schemas (User, Listing, Review)
├── public/         # Static files (CSS, JS, Images)
├── routes/         # Express router files
├── views/          # EJS templates for the UI
├── app.js          # Main entry point of the application
├── cloudConfig.js  # Configuration for cloud storage
└── middleware.js   # Custom authentication & validation middleware
