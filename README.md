# Baharatci Webpage

A modern e-commerce web application inspired by the Baharatci website, built with React, Vite, Redux Toolkit, and Firebase.

The project allows users to browse products, manage their shopping basket, create accounts, and complete the checkout process through a responsive and user-friendly interface.

This clone was developed to practice modern React development, state management, routing, authentication, and e-commerce application architecture.

## Features

* Product catalog
* Product details page
* Shopping basket management
* User registration and login
* Firebase authentication
* Checkout page
* Responsive design
* Animated UI elements
* Coupon popup system
* Product filtering and categorization
* Similar products recommendations
* Toast notifications

## Tech Stack

* React
* Vite
* Redux Toolkit
* React Router DOM
* Firebase
* Formik
* Yup
* Ant Design
* Swiper.js
* AOS
* React Toastify

## Project Structure

```text
src/
├── app/
│   └── store.js
├── slices/
│   ├── authSlice.js
│   ├── basketSlice.js
│   └── navbarSlice.js
├── components/
├── pages/
├── router/
├── services/
├── validation/
├── firebase/
└── assets/
```

## Pages

* Home
* Products
* Product Details
* About
* Blog
* Contact
* Login
* Register
* Checkout
* Error Page

## Main Functionalities

### Authentication

Users can:

* Register new accounts
* Login securely
* Maintain authentication state using Firebase

### Shopping Basket

Users can:

* Add products to basket
* Remove products
* Update quantities
* Review order details before checkout

### Product Categories

The application includes various product sections such as:

* Spices
* Natural Herbs
* Natural Oils
* Dried Fruits
* Cake Ingredients
* Discounted Products
* Best Sellers

## Installation

Clone the repository:

```bash
git clone https://github.com/Habibov97/Baharatci-clone.git
cd Baharatci-clone
```

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

## Available Scripts

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

## Demo

GitHub Pages deployment:

```text
https://habibov97.github.io/Baharatci-Clone/
```

## Learning Goals

This project was created to gain hands-on experience with:

* React component architecture
* Redux Toolkit state management
* Firebase authentication
* Form validation with Formik and Yup
* Routing and navigation
* Building scalable e-commerce interfaces

## Author

Developed by Habibov97

## License

This project is intended for educational and portfolio purposes.
