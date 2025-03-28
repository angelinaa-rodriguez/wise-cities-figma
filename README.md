# Wise Cities – E-Commerce Frontend & Backend Project

This project is a take-home technical assignment for the Spring Software Engineering Internship at Wise Cities. It is a full-stack e-commerce website featuring a Home Page and Product Page built using **Next.js**, **Tailwind CSS**, **Next UI**, and **MikroORM** with a PostgreSQL database.

---

## ✨ Features

### 🏠 Home Page
- Grid layout of product cards displaying:
  - Image
  - Name
  - Price
  - "Add to Cart" button
- Fully responsive layout using Tailwind CSS
- Styled to match pixel-perfect Figma design

### 📄 Product Page
- Detailed view for a selected product:
  - Large image, name, description, price
  - Quantity selector and "Add to Cart"
- Section for similar products

### 🛒 Cart Functionality
- "Add to Cart" buttons update a global cart state
- Tracks product quantities

---

## 🧰 Tech Stack

| Tech        | Role                          |
|-------------|-------------------------------|
| Next.js     | Framework + Server-side Rendering |
| Tailwind CSS| Styling UI components         |
| Next UI     | Pre-built styled UI components |
| MikroORM    | ORM for managing the database |
| PostgreSQL  | Database                      |

---

## 🗄️ Database Schema

### `Product`
- `id` (Primary Key)
- `name` (String)
- `description` (Text)
- `price` (Float)
- `imageUrl` (String)

### `Cart`
- `id` (Primary Key)
- `product` (Many-to-one relationship with Product)
- `quantity` (Integer)

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/angelinaa-rodriguez/wise-cities-figma.git
cd wise-cities-figma
