# React Redux Task

This project demonstrates the use of React's `Redux` to handle a shopping cart system. It enables users to adjust item quantities, with the total quantity and amount updating automatically.

## Features

- Fetches JSON data to populate the cart.
- Displays each item's title, description, price, and quantity.
- Allows users to increment or decrement item quantities.
- Dynamically updates the total quantity and total amount.

### Fetching Data

The application fetches JSON data from the following URL:

[https://drive.google.com/file/d/1fOadeM1liwbUK38z92F0XYugk2jwqK2r/view?usp=share_link](https://drive.google.com/file/d/1fOadeM1liwbUK38z92F0XYugk2jwqK2r/view?usp=share_link)

Use the data from this link to create a cart page that displays each item's price, quantity, total quantity, and total amount.

## Demo

Check out the live project [here](https://getciya7-react-redux-task.netlify.app/).

---

## Folder Structure

```
react-redux-task/
├── node_modules/
├── public/
│   └── react.svg
├── src/
│   ├── data/
|   |   └── product.json
│   ├── reducers/
|   |   ├── cartReducer.js
│   |   └── cartSlice.js
│   ├── App.css
│   ├── App.jsx
│   ├── Cart.jsx
│   ├── main.jsx
│   ├── ProductCard.jsx
|   └── store.js
├── .gitignore
├── index.html
├── package.json
├── README.md
├── vite.config.js
```

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/getciya7/react-redux-task.git
```

2. Navigate to the project directory:

```bash
cd react-redux-task
```

3. Install the dependencies:

```bash
npm install
```

---

## Usage

1. Start the development server:

```bash
npm run dev
```

2. Open your browser and go to `http://localhost:5173` to see the application.

---

## Acknowledgements

- [React](https://reactjs.org) for the JavaScript library.
- [Vite](https://vitejs.dev) for the build tool.
- [Netlify](https://app.netlify.com)For providing the platform to deploy the application.

---
