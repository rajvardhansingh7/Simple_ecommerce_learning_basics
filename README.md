# 🛒 Simple E-Commerce Web App

A clean, lightweight e-commerce demo built using **HTML**, **CSS**, and **JavaScript**.  
This project demonstrates basic shopping cart functionality — users can add products, remove them, and see the total update dynamically — all within a beautiful dark-themed interface.

---

## 🌐 Live Demo

🖼️ **Project Preview:**  
![Project Demo](https://github.com/rajvardhansingh7/Simple_ecommerce_learning_basics/blob/main/image.png)

---

## 📁 Project Structure

├── index.html # Main HTML structure
├── styles.css # Styling for layout and dark theme
└── script.js # JavaScript logic for cart functionality

## ⚙️ Features

- 🧩 **Product Listing:** Dynamically generated product list from JavaScript  
- 🛍️ **Add to Cart:** Add products with a single click  
- 🗑️ **Remove from Cart:** Delete items with real-time total update  
- 💰 **Dynamic Total:** Automatically updates when items are added or removed  
- ✅ **Checkout Simulation:** Clears cart and displays a success alert  
- 🌑 **Modern Dark UI:** Elegant, minimal, and responsive design  

## 🧠 How It Works

1. Products are defined inside `script.js`:
   ```js
   const products = [
     { id: 1, name: "Product 1", price: 29.99 },
     { id: 2, name: "Product 2", price: 19.99 },
     { id: 3, name: "Product 3", price: 59.99 },
   ];
Each product is rendered dynamically in the product list.

Clicking “Add to Cart” adds the product to the cart and updates the total.

Each cart item has a 🗑️ Remove button that updates the total price when clicked.
The Checkout button clears the cart and shows a success alert.

🧰 Technologies Used
HTML5 – Page structure
CSS3 – Dark mode styling and layout
Vanilla JavaScript (ES6) – Dynamic interactivity

🚀 Run Locally
Clone this repository:
bash
Copy code
git clone https://github.com/rajvardhansingh7/Simple_ecommerce_learning_basics.git
Navigate into the folder:

bash
Copy code
cd Simple_ecommerce_learning_basics
Open the project in your browser:

bash
Copy code
start index.html      # Windows
open index.html       # macOS
xdg-open index.html   # Linux
🧩 Future Improvements
🧾 Add product images and descriptions

🧮 Add quantity selection and update cart items dynamically

💳 Implement real checkout and payment integration

🔐 Use LocalStorage to save cart data between sessions

🧑‍💻 Author
Rajvardhan Singh
📦 GitHub Profile

🪪 License
This project is licensed under the MIT License — you are free to use and modify it with attribution.

yaml
Copy code

---

✅ Just save this as **`README.md`** in your project folder → commit → push to GitHub.  
Your repo page will then automatically display it beautifully.
