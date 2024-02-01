# Commerce 360

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node Version](https://img.shields.io/badge/node.js-14.x%20|%2016.x%20|%2018.x-brightgreen)](https://nodejs.org/en/download/)
<a href="https://img.shields.io/github/languages/count/akhilreddy030/Commerce360">
  <img src="https://img.shields.io/github/languages/count/akhilreddy030/Commerce360" alt="Languages Count"/>
</a>

## Description
**Commerce 360** is a full-featured eCommerce platform built using the MERN stack (MongoDB, Express.js, React, and Node.js). It provides a seamless shopping experience for users, allowing them to browse products, manage their cart, and securely complete purchases. The platform includes advanced features such as admin management tools, responsive design, and integration with a payment gateway.

## Features
- **User Authentication and Authorization**: Secure login and registration using JWT.
- **Product Management**: Full CRUD capabilities for products, with support for multiple image uploads via Cloudinary.
- **Shopping Cart**: Add, remove, and update products in a user-friendly cart interface.
- **Checkout Process**: Streamlined order placement with integrated payment processing.
- **Order Management**: Track order status and history for both users and admins.
- **Admin Dashboard**: Manage products, orders, and users through an intuitive interface.
- **Responsive Design**: Optimized for both desktop and mobile users.
- **Search and Filter**: Advanced product search and filtering options.
- **Reviews and Ratings**: Allow users to leave detailed feedback for products.

## Technologies Used
- **Frontend**: React.js, Redux, React Router, Axios, Bootstrap
- **Backend**: Node.js, Express.js, JWT for authentication
- **Database**: MongoDB, Mongoose
- **Image Hosting**: Cloudinary
- **Payment Gateway**: Stripe (or another of your choice)
- **Version Control**: Git

## Installation and Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/akhilreddy030/Commerce360.git
    cd Commerce360
    ```

2. **Install backend dependencies**:
    ```bash
    cd backend
    npm install
    ```

3. **Install frontend dependencies**:
    ```bash
    cd ../frontend
    npm install
    ```

4. **Start the development servers**:
    - Backend server:
      ```bash
      cd ../backend
      npm start
      ```
    - Frontend server:
      ```bash
      cd ../frontend
      npm run dev
      ```

## Configure Environment Variables
- Create a **.env** file in the backend directory and include the following:
    ```plaintext
    PORT=4000
    MONGO_URI=<Your_MongoDB_URI>
    STRIPE_API_KEY=<Your_Stripe_API_Key>
    STRIPE_SECRET_KEY=<Your_Stripe_Secret_Key>
    JWT_SECRET=<Your_JWT_Secret>
    JWT_LIFETIME=30d
    JWT_COOKIE_EXPIRE=7
    SMTP_SERVICE=<Your_SMTP_Service>
    SMTP_MAIL=<Your_SMTP_Email>
    SMTP_PASSWORD=<Your_SMTP_Password>
    SMTP_HOST=<Your_SMTP_Host>
    SMTP_PORT=<Your_SMTP_Port>
    CLOUDINARY_NAME=<Your_Cloudinary_Account_Name>
    CLOUDINARY_API_KEY=<Your_Cloudinary_API_Key>
    CLOUDINARY_API_SECRET=<Your_Cloudinary_API_Secret>
    ```

## Usage
1. Open your browser and navigate to **http://localhost:5173** to access the frontend.
2. Use Postman or another API client to interact with the backend via **http://localhost:4000**.

## Contributing
Contributions are welcome! If you’d like to contribute, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries or feedback, please reach out at **pabbathireddyakhilreddy@gmail.com**.
