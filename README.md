
 Wanderlust – Web-Based Accommodation Rental and Booking Platform
 Project Overview

**Wanderlust** is a full-stack MERN web application inspired by Airbnb, built with **MongoDB, Express.js, Node.js, and EJS templates**. The platform allows users to:
* Browse and search for properties
* Create, edit, and delete property listings
* Upload images
* Write reviews
* Authenticate securely
* Explore locations with dynamic maps

The project is structured using **MVC architecture**, follows **RESTful principles**, and is deployed on **Render**.

 Features

 Core Features

* User **signup, login, logout**
* **CRUD operations** for property listings
* **Review system** linked to users
* **Secure authentication & authorization** (only owners can edit/delete listings)
* **Server-side and client-side validation** using Joi
* **Custom error handling** with ExpressError and wrapAsync

 Advanced Features

* **Image upload** using Multer and Cloudinary
* **Dynamic map integration** with Mapbox
* **Sessions, cookies, and flash messages** for user feedback
* Modularized routes using **Express Router**
* **MVC architecture** for scalability and maintainability
* **Frontend UI improvements**: filters, interactive forms, responsive design

 Software & Tools Used

| Component           | Tool / Library               | Purpose                           |
| ------------------- | ---------------------------- | --------------------------------- |
| IDE / Editor        | VS Code                      | Development & debugging           |
| Backend Runtime     | Node.js                      | Server-side JS execution          |
| Backend Framework   | Express.js                   | Routing, middleware, REST API     |
| Database            | MongoDB & Mongoose           | Data storage and modeling         |
| Authentication      | Passport.js, Express-session | Secure login & session management |
| Validation          | Joi                          | Server-side input validation      |
| File Upload         | Multer                       | Handle image uploads              |
| Cloud Storage       | Cloudinary                   | Store images securely in cloud    |
| Maps & Geocoding    | Mapbox                       | Interactive maps & location data  |
| Frontend Templating | EJS                          | Server-side HTML rendering        |
| Deployment          | Render                       | Hosting the web application       |

 Future Enhancements

* Payment gateway integration
* Booking system
* Admin dashboard for listings management
* Real-time notifications


