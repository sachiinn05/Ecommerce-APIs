# E-commerce APIs

This project provides a backend API for an e-commerce application, built using Node.js and Express.

## Features
- User authentication (signup/login)
- Product management (add, update, delete, get products)
- Cart management
- Order processing
- Error handling and logging
- API documentation with Swagger

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/sachiinn05/Ecommerce-APIs.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Ecommerce-APIs
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Running the Server

Start the development server:
```sh
npm start
```

Or use nodemon for automatic restarts:
```sh
npm run dev
```

## API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST   | `/auth/signup` | Register a new user |
| POST   | `/auth/login` | User login |
| GET    | `/products` | Get all products |
| POST   | `/products` | Add a new product |
| GET    | `/cart` | Get cart items |
| POST   | `/cart` | Add item to cart |
| DELETE | `/cart/:id` | Remove item from cart |



## API Documentation
Swagger documentation is available at:
```
http://localhost:5000/api-docs
```



## Contact Me
For any queries or support, feel free to reach out:
- **Email:** sachinsingh6386@gmail.com
- **GitHub:** [sachiinn05](https://github.com/sachiinn05)

## License
This project is licensed under the MIT License.
