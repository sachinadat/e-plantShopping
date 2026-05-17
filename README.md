# e-plantShopping

A modern, responsive e-commerce web application for shopping plants online. Built with React, Vite, and Redux for efficient state management.

## Features

- 🌱 Browse a curated collection of plants
- 🛒 Add/remove items from shopping cart
- 💾 Persistent cart state management with Redux
- 📱 Fully responsive design
- ⚡ Fast performance with Vite build tool
- 🎨 Clean and intuitive user interface

## Tech Stack

- **Frontend Framework**: React 18.2.0
- **Build Tool**: Vite 5.2.0
- **State Management**: Redux Toolkit 2.2.3
- **Styling**: CSS
- **Package Manager**: npm

## Repository name 
- e-plantShopping

## Project Structure

```
e-plantShopping/
├── src/
│   ├── components/
│   │   ├── App.jsx           # Main application component
│   │   ├── ProductList.jsx   # Product listing page
│   │   ├── CartItem.jsx      # Shopping cart item
│   │   └── AboutUs.jsx       # About page
│   ├── store.js              # Redux store configuration
│   ├── CartSlice.jsx         # Cart reducer slice
│   ├── main.jsx              # Application entry point
│   ├── App.css
│   ├── index.css
│   └── assets/               # Static assets
├── public/                    # Public assets
├── vite.config.js           # Vite configuration
├── index.html
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/e-plantShopping.git
cd e-plantShopping
```

2. Install dependencies:
```bash
npm install
```

### Development

Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Build

Create a production build:
```bash
npm run build
```

### Preview

Preview the production build locally:
```bash
npm run preview
```

### Linting

Check code quality:
```bash
npm run lint
```

## Usage

1. **Browse Products**: Navigate through the product list to explore available plants
2. **Add to Cart**: Click the add button on any plant to add it to your shopping cart
3. **Manage Cart**: View and modify items in your shopping cart
4. **View Details**: Check the About Us page for more information about the store

## Redux State Management

The application uses Redux Toolkit for state management:

- **CartSlice**: Manages the shopping cart state (add/remove items, update quantities)
- **Store**: Central Redux store configuration

## License

This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

## Support

For support, please open an issue on the GitHub repository.

---

Made with 🌿 for plant lovers