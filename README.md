# StayHub – Luxury Stays & Unique Getaways

StayHub is a full-stack web application that allows users to discover, create, and review luxury stays and unique travel experiences around the world. Built with Node.js, Express, MongoDB, and EJS, it provides a smooth and responsive experience with authentication, maps, and image uploads.

---
## 🌐 Live Demo

👉 [https://staynest-wa54.onrender.com]

---
## 💻 GitHub Repository

👉 [https://github.com/NileshKumawat03/StayNest.git]

---
## 🚀 Features

- Search listings by title, location, or country
- Filter listings by category
- Create, edit, and delete listings
- User authentication (Register/Login/Logout)
- Add reviews and ratings
- Interactive map with geo-location
- Image upload using Cloudinary
- Protected routes for logged-in users
- Fully responsive design

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- EJS (templating)

### Backend
- Node.js
- Express.js

### Database
- MongoDB Atlas
- Mongoose ODM

### Authentication
- Passport.js
- Express-session

### Cloud Services
- Cloudinary (image storage)
- OpenStreetMap API (Nominatim for geocoding)

---

## 📁 Project Structure

```
Project-StayHub/
├── controllers/          # Request handlers
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
├── models/             # Database schemas
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── routes/             # Route definitions
│   ├── listing.js
│   ├── review.js
│   └── user.js
├── views/              # EJS templates
│   ├── includes/
│   ├── layouts/
│   ├── listings/
│   └── user/
├── public/             # Static files
│   ├── css/
│   └── js/
├── utils/              # Utility functions
├── init/               # Database initialization
├── middleware.js       # Middleware functions
├── app.js              # Main application file
├── cloudConfig.js      # Cloudinary configuration
└── package.json       # Dependencies
```
## 🔐 Authentication

- User registration and login system
- Session-based authentication with Passport.js
- Protected routes for creating, editing, and deleting listings
- Ownership validation (users can only modify their own listings)

---

## 🗺️ Map Feature

- Uses OpenStreetMap API (Nominatim) for geocoding
- Converts location addresses to coordinates
- Stores GeoJSON in MongoDB
- Displays interactive map with Leaflet.js

---

## 📸 Image Upload

- Cloudinary integration for image storage
- Secure file upload handling
- Image URL and filename saved in database

---

## ⭐ Show Your Support

If you like this project:

1. ⭐ Star the repository
2. 🍴 Fork it
3. 🔥 Improve it

---

## 📄 License

This project is licensed under the MIT License.

---

*Built with ❤️ using Node.js, Express, MongoDB, and EJS*
