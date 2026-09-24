# 🏡 Wanderlust

Wanderlust is a full-stack web application for discovering and managing travel and accommodation listings. Users can browse properties, create and manage their own listings, upload images, and add reviews.

## 🚀 Live Demo

🔗 **[Visit Wanderlust](https://wanderlust-project-qm80.onrender.com)**


## 🚀 Features

* User registration, login and logout
* User authentication and authorization
* Create, edit and delete listings
* Upload and manage listing images
* View detailed listing information
* Add and delete reviews
* Ratings and reviews for listings
* Interactive maps and location-based listing display
* Server-side validation
* Centralized error handling
* Flash messages for user feedback
* Session management
* Responsive user interface

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* Bootstrap
* JavaScript
* EJS

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose
* MongoDB Atlas

### Authentication & Authorization

* Passport.js
* Passport-Local
* Passport-Local-Mongoose
* Express-Session
* Connect-Mongo

### Cloud Services

* Cloudinary – Image upload and storage
* Mapbox – Maps and location-based services

### Other Tools & Libraries

* Multer
* Joi
* EJS-Mate
* Method-Override
* Connect-Flash
* Dotenv
* Git & GitHub

## 🏗️ Project Architecture

The project follows the **MVC (Model-View-Controller)** architecture.

```text
Wanderlust/
│
├── controllers/       # Application/business logic
├── init/              # Database initialization/seed data
├── models/            # Mongoose database models
├── public/            # CSS, JavaScript and static assets
├── routes/            # Application routes
├── utils/             # Utility/helper functions
├── views/             # EJS templates
│
├── .gitignore         # Files ignored by Git
├── app.js             # Main application/server file
├── cloudConfig.js     # Cloudinary configuration
├── middleware.js      # Custom middleware
├── schema.js          # Joi validation schemas
├── package.json       # Project dependencies and scripts
└── package-lock.json  # Dependency lock file
```
## 🌐 Deployment

The application is deployed using **Render** and uses **MongoDB Atlas** for cloud database management.

## 👩‍💻 Created By:

**Pratiksha Mule**
