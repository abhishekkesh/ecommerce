# 11_Ecommerce_Web

A modern e-commerce web application built with React, Vite, and TailwindCSS. This project demonstrates a responsive and interactive user interface with features like dark mode, product listings, testimonials, and more.

## Features

- **Responsive Design**: Fully responsive layout with TailwindCSS.
- **Dark Mode**: Toggle between light and dark themes.
- **Product Listings**: Display top-rated and trending products.
- **Hero Section**: Dynamic hero slider with promotional content.
- **Testimonials**: Customer reviews displayed in a carousel.
- **Order Popup**: Interactive popup for placing orders.
- **Animations**: Smooth animations using AOS (Animate On Scroll).

## Tech Stack

- **React**: Frontend library for building user interfaces.
- **Vite**: Fast build tool for modern web projects.
- **TailwindCSS**: Utility-first CSS framework for styling.
- **AOS**: Library for scroll animations.
- **React Slick**: Carousel/slider component for React.
- **React Icons**: Icon library for React.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd ReactProject
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open the application in your browser at `http://localhost:5173`.

## Project Structure

```
ReactProject/
├── public/               # Static assets
├── src/                  # Source code
│   ├── components/       # Reusable components
│   │   ├── Banner/       # Banner section
│   │   ├── Footer/       # Footer section
│   │   ├── Hero/         # Hero section
│   │   ├── Navbar/       # Navigation bar
│   │   ├── Popup/        # Order popup
│   │   ├── Products/     # Product listings
│   │   ├── Subscribe/    # Subscription section
│   │   ├── Testimonials/ # Customer testimonials
│   │   └── TopProducts/  # Top-rated products
│   ├── App.jsx           # Main application component
│   ├── main.jsx          # Entry point
│   └── index.css         # Global styles
├── .eslintrc.cjs         # ESLint configuration
├── tailwind.config.js    # TailwindCSS configuration
├── vite.config.js        # Vite configuration
├── package.json          # Project metadata and dependencies
└── README.md             # Project documentation
```

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm run preview`: Preview the production build.
- `npm run lint`: Run ESLint to check for code quality.

## Dependencies

- **React**: `^18.2.0`
- **React DOM**: `^18.2.0`
- **React Icons**: `^4.12.0`
- **React Slick**: `^0.29.0`
- **Slick Carousel**: `^1.8.1`
- **AOS**: `^2.3.4`

## Dev Dependencies

- **Vite**: `^5.0.8`
- **TailwindCSS**: `^3.4.0`
- **ESLint**: `^8.55.0`
- **PostCSS**: `^8.4.32`

## License

This project is licensed under the MIT License. Feel free to use and modify it as per your needs.