# E-Store MEAN Stack Project

A full-stack **E-commerce Web Application** built using the **MEAN stack** (MongoDB, Express.js, Angular, Node.js).  
This project includes separate dashboards for **customers** and **admins**, with a REST API backend.

---

## 🔹 Features

### Customer (Shop)  
- Browse products by category  
- View product details  
- Add products to cart  
- Place orders  

### Admin Dashboard  
- Manage products (Create, Read, Update, Delete)  
- Manage orders and track status  
- Manage users  

### Backend  
- RESTful APIs with **Node.js** and **Express.js**  
- Database: **MongoDB** (Mongoose ORM)  
- User authentication and role management  

---

## 💻 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Angular |
| Backend | Node.js + Express.js |
| Database | MongoDB |
| ORM | Mongoose |
| Version Control | Git / GitHub |

---

## ⚡ Installation

### Prerequisites
- Node.js & npm installed
- Angular CLI installed globally
- MongoDB installed and running

### Steps

1. **Clone the repository**
```bash
git clone https://github.com/chakrinani/E---Store.git
cd E---Store/e-store-main
````

2. **Install frontend dependencies**

```bash
npm install
```

3. **Run the Angular frontend**

* Customer shop:

```bash
ng serve shop
```

* Admin dashboard:

```bash
ng serve admin
```

Open your browser at: `http://localhost:4200` (shop) or `http://localhost:4201` (admin)

4. **Install backend dependencies**

```bash
cd server
npm install
```

5. **Start backend server**

```bash
npm start
```

Backend runs at: `http://localhost:3000`

---

## 🔧 Project Structure

```
e-store-main/
├── e-store-main/        # Angular workspace
│   ├── admin/           # Admin Angular project
│   ├── shop/            # Customer Angular project
│   └── angular.json     # Angular workspace config
└── server/              # Node.js + Express backend
```

---



## 📌 Notes

* Make sure MongoDB is running locally or update the connection string in `server/config.js`.
* You can customize products, users, and other data by modifying the MongoDB collections.

---

Do you want me to do that?
```
