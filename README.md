# AdminPro---Product-Inventory-Management-Dashboard-
*AdminPro** is a lightweight, single-page application designed for small to medium-sized businesses to manage their product catalog efficiently. It provides an intuitive interface for adding, editing, deleting, and viewing products with real-time updates and comprehensive filtering capabilities.
# 🎯 Project Objectives

- **Simplify Inventory Management**: Provide an easy-to-use interface for managing products without complex backend dependencies
- **Real-time Data Persistence**: Store product data locally using browser localStorage for instant availability
- **Professional UI/UX**: Create a modern, responsive design that works seamlessly across desktop and mobile devices
- **Scalability**: Build a foundation that can be easily extended with backend integration, authentication, or advanced features

## ✨ Key Features

### Dashboard Overview
- **Total Products Count**: Quick view of all products in inventory
- **Category Tracking**: Track the number of unique product categories
- **Inventory Valuation**: Calculate total value based on product price and stock quantity
- **Recently Added Products**: Display latest additions to the catalog with key metrics

### Product Management
- **View All Products**: Comprehensive product table with search and filter capabilities
- **Add Products**: Create new products with name, category, price, stock quantity, and image URL
- **Edit Products**: Modify existing product details with pre-filled form data
- **Delete Products**: Remove products from inventory with confirmation dialog
- **Search & Filter**: Find products by name, description, or category

### Data Management
- **Local Storage**: All data persists in the browser's localStorage (survives page refresh)
- **Form Validation**: Comprehensive validation for product fields (required fields, numeric validation)
- **Stock Status Indicators**: Visual indicators showing stock levels (green for >10, yellow for 1-10, red for 0)
- **Image Preview**: Display product images directly in the inventory list and form preview

## 🛠️ Tech Stack

- **Frontend Framework**: React 19.2.4
- **Styling**: Tailwind CSS 4.2.1 + Tailwind Play CDN
- **Routing**: React Router DOM 7.13.1
- **Icons**: Lucide React 0.575.0
- **State Management**: React Hooks (useState, useEffect)
- **Data Persistence**: Browser localStorage
- **Build Tool**: Create React App (react-scripts 5.0.1)

## 📁 Project Structure

```
my-app/
├── public/
│   ├── index.html       # Main HTML template with Tailwind CDN
│   └── manifest.json    # PWA metadata
├── src/
│   ├── components/
│   │   ├── DashboardCard.jsx      # Reusable dashboard metric card
│   │   ├── Navbar.jsx              # Top navigation bar
│   │   ├── ProductForm.jsx          # Product add/edit form with validation
│   │   ├── ProductTable.jsx         # Product inventory table with actions
│   │   └── Sidebar.jsx              # Left sidebar navigation
│   ├── pages/
│   │   ├── AddEditProduct.jsx      # Add/Edit product page
│   │   ├── Dashboard.jsx            # Dashboard overview page
│   │   └── Products.jsx             # Products inventory page
│   ├── utils/
│   │   └── localStorageHelper.js   # Utility functions for data persistence
│   ├── App.js           # Main app component with routing
│   ├── index.js         # React entry point
│   ├── index.css        # Global styles (Tailwind directives)
│   └── setupTests.js    # Test configuration
├── tailwind.config.js   # Tailwind CSS configuration with custom animations
├── postcss.config.js    # PostCSS configuration
├── package.json         # Project dependencies
└── README.md            # This file
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. **Clone or extract the project**
   ```bash
   cd my-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```
   The app will open automatically at [http://localhost:3000](http://localhost:3000)

