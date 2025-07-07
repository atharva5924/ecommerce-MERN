# 🛒 Mernova - Full Stack E-Commerce Web Application

Mernova is a responsive and scalable full-stack e-commerce platform built using the **MERN** stack (MongoDB, Express.js, React.js, Node.js). It allows users to browse products, manage a shopping cart, securely place orders, and view real-time order history—all in a modern, user-friendly interface.



## 📂 GitHub Repository
> https://github.com/atharva5924/ecommerce-MERN

---

## 🚀 Features

### 👤 User Experience
- 🔍 **Product Browsing**: Search and explore items with pagination and filtering.
- 🛒 **Cart System**: Add/remove items with quantity adjustments.
- 🔐 **Secure Checkout**: End-to-end order flow with input validation.
- 📦 **Order History**: View past orders with live status updates.


---

## 🧰 Tech Stack

| Category        | Technology           |
|----------------|----------------------|
| Frontend        | React.js, Toastify, HTML/CSS |
| Backend         | Node.js, Express.js |
| Database        | MongoDB (Mongoose) |
| Auth            | JWT (JSON Web Tokens) |
| Styling         | CSS Modules / Tailwind (customizable) |
| Dev Tools       | Postman, GitHub, VS Code |
| Performance     | Lazy-loading, query tuning |
| Hosting (Optional) | Vercel / Render / Railway / MongoDB Atlas |

---

## 📊 Design Decisions

- Used **Toastify** for simple global notifications without over-complicating state.
- Opted for **context API** instead of Redux for minimal overhead and faster development.

---
## ⚙️ Installation & Run Locally

### Prerequisites
- Node.js (v16+)
- MongoDB (local or Atlas)
- npm or yarn

### Clone the Repository
```bash
git clone https://github.com/atharva5924/ecommerce-MERN.git
cd ecommerce-MERN
```

## ⚙️ Setup Server

```bash
cd server
npm install
# Add `.env` file with Mongo URI and JWT_SECRET
npm start
```
## ⚙️ Setup Client
```bash
cd client
npm install
npm start
```
---
## 📁 Folder Structure

```bash
ecommerce-MERN/
├── client/          # React frontend
│   └── src/
│       └── components/
│       └── pages/
├── server/          # Node backend
│   └── controllers/
│   └── models/
│   └── routes/
│   └── middlewares/
```
---

## 🔐 Environment Variables
Create a .env file inside the server/ directory:

```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```
---

## 🧪 Testing
20+ test orders created to validate backend routes and frontend states.

Simulated different screen sizes to ensure responsiveness.

Verified lazy loading and optimized query performance (30% page speed gain). 

---

## ✨ Performance Highlights
📦 Lazy-loading of assets and pages

⚡ Query optimization for faster DB interactions

📱 Fully responsive UI across 3 screen sizes

---

## 🙋‍♂️ About Me

Made with ❤️ by **Atharva Nile**

- 📧 Email: [nileatharva20@gmail.com](mailto:nileatharva20@gmail.com)
- 🔗 GitHub: [atharva5924](https://github.com/atharva5924)


---

## 📃 License
This project is licensed under the MIT License.

```bash


Let me know if you'd like a **dark/light GitHub preview**, deployable `vercel.json` or MongoDB Atlas `.env` examples.

```
