# Project 11.1 - Event Handler

This is a simple e-commerce web application built using React.js + vite, styled with Bootstrap. It allows users to browse a catalog of random products, add items to their shopping cart, and view the total price of their selected products. The cart is stored locally using localStorage, ensuring that user selections persist across page reloads

## Features

- **Refined Display**:
  Product catalog display with images, descriptions, ratings, and price.

- **Add Products**:
  Ability to add products to the cart.

- **Modify Quantities**:
  Update product quantities (increase/decrease) in the cart.

- **Discard Items**:  
  Remove products from the cart.

- **Grand Total**:
- Displays total price of items in the cart.

## Folder Structure

```cpp
src/
  ├── Components/
  │    ├── ProductNav.jsx         // Navigation bar component
  │    ├── Products.jsx           // Main component for displaying products and managing the cart
  │    ├── ProductCart.jsx        // Cart component to manage and display cart items
  │    └── ProductsCatalogue.jsx  // Component to render the list of products
  ├── App.jsx                     // Main app component that ties everything together
  ├── App.css                     // Custom styles for the app
  └── index.js                    // Entry point of the application
```

## How to Use

1. **Clone the Repository:**

```bash
  git clone
```

2. **Navigate to the Project Directory:**

```bash
  cd Project-11.1---Event-Handler
```

3. **Install Dependencies:**
   Install the required Dependencies using this command

```bash
  npm install
```

4. **Run the Application:**
   Start the development server

```bash
  npm run dev
```

5. **Open in Browser:**
   Navigate to Localhost url in your web browser to view the application.

## Screenshots

<img width="330" alt="Event Handler - 1" src="./src/Images/Event Handler - 1.png">
<img width="330" alt="Event Handler - 2" src="./src/Images/Event Handler - 2.png">
<img width="330" alt="Event Handler - 3" src="./src/Images/Event Handler - 3.png">
<img width="330" alt="Event Handler - 4" src="./src/Images/Event Handler - 4.png">
<img width="330" alt="Event Handler - 5" src="./src/Images/Event Handler - 5.png">
<img width="330" alt="Event Handler - 6" src="./src/Images/Event Handler - 6.png">

## Technologies Used

- **HTML** : To Structure the App Layout.
- **CSS** : To Style & Enhance the user Interface.
- **JavaScript LocalStorage** :In this app, localStorage is used to save the cart data in the browser, allowing the cart to persist even after the page is reloaded. This ensures that users' selections are maintained across sessions.
- **React + Vite + JSX (JavaScript & XML)** : React + Vite + JSX is a modern stack for building fast web apps. React provides reusable UI components, Vite offers fast development and optimized builds, and JSX allows writing HTML-like code in JavaScript for seamless UI creation.

## License

This Project is Licensed under the MIT License.
