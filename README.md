# Sagar Majoka Paints - E-Commerce Platform

A modern e-commerce platform for a paint shop, featuring a responsive frontend and RESTful backend API.

## 🌟 Features

### Frontend
- **Modern UI/UX**
  - Responsive design with dark mode support
  - Mobile-friendly navigation
  - Mega menu for products and categories
  - Enhanced search with voice search option
  - Shopping cart and user account management

- **Product Management**
  - Product grid display with images
  - Advanced filtering by:
    - Category (Interior, Exterior, Specialty)
    - Price range
  - Product cards with wishlist and cart functionality

- **Color Tools**
  - Color guide with curated palettes
  - Color visualizer tool
  - Color swatch previews

- **User Features**
  - User registration and login
  - Shopping cart
  - Wishlist management
  - Recently viewed products
  - Order tracking

### Backend
- **Authentication System**
  - JWT-based authentication
  - Secure password hashing
  - User registration and login

- **API Endpoints**
  - `/api/health` - Health check
  - `/api/register` - User registration
  - `/api/login` - User authentication
  - `/api/products` - Product management
  - `/api/orders` - Order processing

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/paint-shop.git
cd paint-shop
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The server will start on `http://localhost:3000`

## 📁 Project Structure
```
paint-shop/
├── backend/           # Server-side code
├── css/              # Stylesheets
├── js/               # Client-side scripts
├── images/           # Product images and assets
├── data/             # JSON data files
├── index.html        # Main page
├── products.html     # Product listing
├── cart.html         # Shopping cart
├── login.html        # User login
├── register.html     # User registration
├── server.js         # Main server file
└── package.json      # Project dependencies
```

## 🔧 Technologies Used
- Frontend:
  - HTML5
  - CSS3 (with Flexbox/Grid)
  - JavaScript (ES6+)
  - Font Awesome icons

- Backend:
  - Node.js
  - Express.js
  - JWT for authentication
  - JSON file-based database

## 🌐 API Documentation

### Authentication
- **Register User**
  ```http
  POST /api/register
  Content-Type: application/json

  {
    "name": "User Name",
    "email": "user@example.com",
    "password": "password123",
    "phone": "1234567890"
  }
  ```

- **Login**
  ```http
  POST /api/login
  Content-Type: application/json

  {
    "email": "user@example.com",
    "password": "password123"
  }
  ```

### Products
- **Get All Products**
  ```http
  GET /api/products
  ```

- **Get Product by ID**
  ```http
  GET /api/products/:id
  ```

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact
Sagar Majoka - [@sagar_majoka42](https://www.instagram.com/sagar_majoka42/) - majokasagar524@gmail.com

Project Link: [https://github.com/yourusername/paint-shop](https://github.com/yourusername/paint-shop) 
