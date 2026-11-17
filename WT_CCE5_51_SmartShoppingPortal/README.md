# 🛍️ Smart Shopping Portal

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> A modern, fast, and responsive Single Page Application (SPA) built entirely with vanilla web technologies for the Web Technology CCE Unit V Mini Project.

---

## 📋 Academic Details
* **Subject:** Web Technology 1 
* **Assignment:** CCE-5 | Unit V Mini Project
* **Roll No:** 57
* **Institution:** D. Y. Patil College of Engineering, Akurdi

---

## ✨ Features

* 🚀 **Single Page Application (SPA):** Custom client-side, hash-based routing ensures seamless navigation across Home, Products, Cart, and Checkout pages without full page reloads.
* 📦 **Dynamic Data Fetching:** Product catalog is populated dynamically from a `products.json` file using the asynchronous `fetch` API.
* 🛒 **Persistent Shopping Cart:** Cart state is managed using `localStorage`, ensuring users don't lose their selected items even if they accidentally refresh the page.
* 📱 **Responsive Design:** Fully responsive layout built with CSS Grid and Flexbox, providing an optimal viewing experience on both desktop and mobile devices.
* 🔍 **Real-time Search & Filtering:** Instantly filter products by category or search through the catalog by name.
* 🛡️ **Client-Side Validation:** The checkout form features strict Regex-based validation for names, emails, 10-digit phone numbers, and 6-digit PIN codes with dynamic visual error feedback.

---

## 🛠️ Assignment Requirements Checklist

- [x] **SPA-style navigation** without page reload
- [x] **Client-side routing** using plain JavaScript
- [x] **Responsive UI** adapting to different screen sizes
- [x] **Dynamic data loading** via JSON parsing
- [x] **Client-side validation** for form inputs

---

## 📂 Project Structure

```text
📦 WT_CCE5_51_SmartShoppingPortal
 ┣ 📜 index.html      # Main HTML entry point & Layout wrapper
 ┣ 📜 style.css       # Custom CSS styling & responsive media queries
 ┣ 📜 app.js          # Core logic: Router, Cart, UI Rendering, Validation
 ┣ 📜 products.json   # Mock database containing product/category data
 ┗ 📜 README.md       # Project documentation
```

---

## 🚀 How to Run Locally

Because this project uses the `fetch` API to load the product data, it must be served over an HTTP server (simply double-clicking `index.html` will cause CORS errors). 

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/WT_CCE5_51_SmartShoppingPortal.git
   ```
2. **Open the project in VS Code:**
   ```bash
   cd WT_CCE5_51_SmartShoppingPortal
   code .
   ```
3. **Run with Live Server:**
   * Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code.
   * Right-click `index.html` and select **"Open with Live Server"**.
   * The app will open in your default browser at `http://127.0.0.1:5500`.

---


| Home Page | Products Page | Cart |
| :---: | :---: | :---: |
| <img src="screenshots/home.png" width="250" alt="Home Screen"> | <img src="screenshots/products.png" width="250" alt="Products Screen"> | <img src="screenshots/cart.png" width="250" alt="Cart Screen"> |

---

