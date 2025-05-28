📦 Inventory Control Dashboard for SMEs

This is a full-stack inventory management system designed for small and medium-sized businesses (SMEs). It includes a **Node.js** backend with a RESTful API, administrator login, product and stock management, and a simple web interface built with either plain HTML or React.

---

## 🚀 Features

- 🛒 Add and edit products
- 📉 Record stock entries and exits
- 📊 Generate reports for low or out-of-stock items
- 🔐 Secure admin login using JWT
- 📄 Track product movement history
- 🌐 Web interface using HTML or React (optional)

---

## 🛠️ Tech Stack

- Node.js + Express
- MySQL or PostgreSQL
- JWT Authentication
- HTML + CSS (or React for frontend)
- Docker (for easy deployment)
- Postman (for API testing)

---

## 🔧 Main API Endpoints

| Method | Route                     | Description                      |
|--------|---------------------------|----------------------------------|
| POST   | /api/admin/login          | Admin login                      |
| GET    | /api/products             | Get list of products             |
| POST   | /api/products             | Create new product               |
| PUT    | /api/products/:id         | Update a product                 |
| DELETE | /api/products/:id         | Delete a product                 |
| POST   | /api/stock/in             | Register stock entry             |
| POST   | /api/stock/out            | Register stock exit              |
| GET    | /api/reports/low-stock    | Get low/out-of-stock products    |

---

## 📂 Project Structure

```

📁 src/
├── controllers/
├── models/
├── routes/
├── middleware/
├── config/
└── app.js
📁 public/ (if using HTML)
📄 .env
📄 Dockerfile
📄 README.md

````

---

## 🧪 How to Run

### 🔸 Local Setup

1. Clone the repository  
2. Set up your `.env` file with DB credentials  
3. Install dependencies:

```bash
npm install
````

4. Start the development server:

```bash
npm run dev
```

---

### 🔸 Docker Setup

If you prefer Docker:

```bash
docker-compose up --build
```

---

## 📌 Future Features (Roadmap)

* [ ] React-based Admin Panel
* [ ] Automatic stock reports via email
* [ ] Export reports to Excel or PDF
* [ ] Product movement history
* [ ] Multi-user and permission roles

---

## 👨‍💻 Author

Developed by [Giuliano Sacco](https://github.com/your_username)
Backend Developer | Computer & Economics Engineering | Uruguay 🇺🇾

---

## 📄 License

MIT License – Free to use, modify, and distribute

