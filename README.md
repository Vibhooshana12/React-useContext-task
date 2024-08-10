# React useContext Task

This project demonstrates the implementation of a shopping cart in a React application using react-router-dom and ContextAPI for state management.

## Demo
Check out the live demo of the project [here](https://react-usecontext-vibhooshana.netlify.app/))

## Functionalities

- Cart Management: The cart page displays each item's price, quantity, and allows users to increase or decrease quantities.
- Dynamic Updates: Adjusting the quantity of items in the cart automatically updates the total quantity and total amount.
- Context API: All state management for the cart is handled using React's Context API, ensuring a clean and efficient state flow across the app.

## Folder Structure

reactrouter-app/

├── node_modules/

├── public/

│   ├── favicon.ico

│   └── index.html

├── src/

│   ├── components/

│   │   ├── NavBar.jsx

│   │   ├── Home.jsx

│   │   ├── CartContext.jsx

│   │   ├── Cart.jsx

│   │   ├── Starrating.jsx

│   ├── data/

│   │   ├── Products.jsx

│   ├── App.css

│   ├── App.jsx

│   ├── index.css

│   ├── index.js

├── .gitignore

├── package.json

├── README.md


## Project Setup

1. Set up your React application:

```bash

npx create-react-app reactrouter-app
cd reactrouter-app

```
2. Install react-router-dom:

```bash

npm install react-router-dom

```
3. Install dependencies:
   
```bash
  npm install react-router-dom @mui/material @emotion/react @emotion/styled @mui/icons-material
```

4. Add Components

Create the following components in the src/components directory:

- `NavBar.jsx`: The sticky navigation bar component containing links to different course categories.
  
- Home.jsx: Displays a list of products with options to add them to the cart.
  
- Cart.jsx: The cart page that shows the selected items, their quantities, and the total amount.

- StarRating.jsx: A component to display and rate products.
  
- CartContext.jsx: Manages the global cart state using React Context API.
  
5. Add Data
   
- `Products`: Contains data details of all the courses
  


5. Set up Routing in App.jsx
   
In the App.jsx file, configure routing using react-router-dom to link the components and pages.
   
6. Run the development server:

To start the development server, use the following command:

```bash

npm start

```
  
7. Open your browser and navigate to http://localhost:3000 to see the application.

## Deployment

To deploy your application:

1. Build the project:

```bash
 npm run build

```

2. Deploy the `build` folder to Netlify.

## Acknowledgements

-React for providing a flexible JavaScript library for building user interfaces.
-React Router for enabling dynamic routing in the application.
-Material UI for providing beautiful and customizable components.
=Netlify for hosting and deploying the application.
