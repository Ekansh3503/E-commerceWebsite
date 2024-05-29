# Full-Stack E-commerce Web Application 

## Description

This is a full-stack e-commerce web application using modern technologies such as React, Node.js, MongoDB, and Stripe. The app will have robust features like category filtering, product sorting, a shopping cart, user authentication with JWT, real-time updates with Redux, secure payments with Stripe, and automatic image uploads using Google Firebase Storage. Additionally, an admin dashboard will be provided for order management and analytics.

## Features

### 🔒 User Authentication and Security
- **JWT Authentication**: The app uses JSON Web Tokens (JWT) for secure user authentication, protecting access to sensitive routes and user-specific data.

### 🔄 Real-time Updates with Redux
- **Real-time Cart Updates**: Utilizing Redux for state management, the shopping cart updates in real-time, allowing users to add, remove, and modify items without refreshing the page.

### 💳 Secure Payments with Stripe
- **Stripe Integration**: Secure payment processing is handled via Stripe, ensuring the safety and security of customer transactions.

### 📊 Analytics and Order Management
- **Admin Dashboard**: The admin panel provides insights into user orders and various analytics, facilitating efficient e-commerce business management.

### 🖼️ Automatic Image Upload
- **Google Firebase Storage**: Product images are automatically uploaded to Google Firebase Storage, simplifying the image handling process.

### 🛠️ Extensive Stack Integration
- **Technology Stack**: This web application covers the integration of various technologies, including React, Node.js, Redux, JWT, Stripe, Google Firebase Storage, and MongoDB.

## Getting Started

### Prerequisites
- Node.js and npm installed on your machine
- MongoDB database setup
- Stripe account for payment processing
- Google Firebase account for image storage

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Ekansh3503/E-commerceWebsite
   ```
   
2. Navigate into the project directory:
   ```bash
   cd fullstack-ecommerce-tutorial
   ```

3. **Install backend dependencies**:
   ```bash
   cd api
   npm install
   ```

4. **Install frontend dependencies**:
   ```bash
   cd ../client
   npm install
   ```

### Configuration

1. **Backend Configuration**:
   - Create a `.env` file in the `backend` directory.
   - Add your MongoDB URI, JWT secret, and Stripe secret key:
     ```env
     MONGODB_URI=your_mongodb_uri
     JWT_SECRET=your_jwt_secret
     STRIPE_SECRET_KEY=your_stripe_secret_key
     ```

2. **Frontend Configuration**:
   - Create a `.env` file in the `frontend` directory.
   - Add your Stripe public key:
     ```env
     REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key
     ```

### Running the Application

1. **Start the backend server**:
   ```bash
   cd api
   npm start
   ```

2. **Start the frontend development server**:
   ```bash
   cd ../client
   npm start
   ```

3. **Access the application**:
   Open your browser and navigate to `http://localhost:3000`.

## Features Breakdown

### User Authentication and Security

- **JWT Implementation**: Securely handle user authentication and authorization using JSON Web Tokens (JWT).
- **Protected Routes**: Ensure only authenticated users can access certain routes and data.

### Real-time Updates with Redux

- **Redux Store**: Manage the application's state efficiently with Redux.
- **Real-time Cart**: Provide a seamless shopping experience with real-time cart updates.

### Secure Payments with Stripe

- **Stripe Integration**: Process payments securely using Stripe's API.
- **Payment Handling**: Ensure transactions are safe and user data is protected.

### Analytics and Order Management

- **Admin Dashboard**: Monitor orders and gain insights into sales and user behavior.
- **Order Management**: Efficiently handle and process user orders.

### Automatic Image Upload

- **Firebase Storage**: Automatically upload and manage product images using Google Firebase Storage.

### Extensive Stack Integration

- **React**: Build a responsive and dynamic frontend.
- **Node.js**: Develop a robust and scalable backend.
- **MongoDB**: Utilize a NoSQL database for flexible data storage.
- **Redux**: Manage application state efficiently.
- **JWT**: Implement secure user authentication.
- **Stripe**: Ensure secure payment processing.
- **Firebase**: Handle image uploads seamlessly.
## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

