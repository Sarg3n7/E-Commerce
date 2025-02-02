# Clyra - E-commerce Application ✨🛍️🚀

Clyra is a fully functional e-commerce platform designed to provide a seamless and engaging online shopping experience. 🛒💻📦 Built with modern web technologies, it offers a robust backend, a dynamic user interface, and efficient data management.

## Features 🎯🔧🚀

- **User Authentication**: Secure login and registration system.
- **Product Management**: Admins can add, edit, and remove products from the catalog.
- **Shopping Cart**: Users can add items to their cart and manage their purchases.
- **Order Processing**: Supports order placement and tracking.
- **Admin Panel**: Dedicated dashboard for product, order, and user management.
- **Responsive Design**: Fully optimized for all screen sizes.
- **Database Integration**: Persistent and scalable data storage using MongoDB.

## Technologies Used 🖥️⚙️📡

- **EJS**: A templating engine that dynamically renders HTML content. 📝🖥️
- **CSS & Tailwind CSS**: A utility-first framework that ensures modern and responsive UI design. 🎨💡
- **JavaScript**: Enables client-side interactivity and server-side functionality. ⚡📜
- **Node.js**: Provides an efficient runtime for scalable backend operations. 🌍🚀
- **Express.js**: A lightweight framework for handling routes, middleware, and API endpoints. 🛠️📌
- **MongoDB**: A NoSQL database optimized for fast and flexible data storage. 🗄️📊
- **Mongoose**: A powerful ODM (Object Data Modeling) library for MongoDB. 🔗📂
- **Multer**: Middleware for handling file uploads like product images. 🖼️📥
- **Passport.js**: Authentication middleware supporting various login strategies. 🔐🔑
- **Bcrypt**: A secure password hashing library. 🔒🔑
- **Express-session**: Manages user sessions for a persistent login experience. 🛠️🗂️
- **Dotenv**: Loads environment variables to keep sensitive data secure. 📁🔏

## Installation 🛠️📦🚀

### 1. Clone the Repository 📂🔗💻
```bash
git clone https://github.com/yourusername/Clyra.git
cd Clyra
```

### 2. Install Dependencies 📥📜⚙️
```bash
npm install
```

### 3. Setup Environment Variables 🌎🔑🔏
Create a `.env` file in the root directory and add the following:
```plaintext
PORT=3000
MONGO_URI=your_mongodb_connection_string
SESSION_SECRET=your_secret_key
```
Replace `your_mongodb_connection_string` and `your_secret_key` with actual values.

### 4. Start the Application 🚀📡
```bash
npm start
```

For development mode with live reload: 🔄⚡
```bash
npx nodemon app.js
```

## How to Run 🌐💻🛍️
- Open your browser and go to `http://localhost:3000`
- Register/Login to start shopping
- Access the admin panel at `http://localhost:3000/admin`

## Contributing 🤝📜🚀
We welcome contributions! Feel free to submit a pull request to help improve Clyra. 🚀💡✨

## License 📜⚖️✅
This project is licensed under the MIT License. 🏛️📜✅

