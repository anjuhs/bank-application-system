# 🏦 Bank Application System (REST API)

A backend banking system designed to manage customer accounts and transactions using a relational database, exposed via RESTful APIs.

---

## 🚀 Features

* Create new customer accounts
* Retrieve account details
* Update customer information
* Delete accounts
* Perform basic transactions (deposit/withdraw)

---

## 🧠 Tech Stack

* **Python (FastAPI / Flask)** – Backend API
* **SQL (MySQL / SQLite)** – Database
* **REST API** – Communication layer

---

## 📡 API Endpoints

| Method | Endpoint       | Description        |
| ------ | -------------- | ------------------ |
| POST   | /accounts      | Create new account |
| GET    | /accounts      | Get all accounts   |
| GET    | /accounts/{id} | Get account by ID  |
| PUT    | /accounts/{id} | Update account     |
| DELETE | /accounts/{id} | Delete account     |
| POST   | /transactions  | Deposit/Withdraw   |

---

## 🗄️ Database Design

The system stores customer data with fields such as:

* Account Number (Primary Key)
* Customer Name
* IFSC Code
* Balance

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/anjuhs/bank-application-system.git
cd bank-application-system
```

2. Install dependencies

```bash
pip install fastapi uvicorn
```

3. Run the server

```bash
uvicorn app:app --reload
```

4. Open in browser:

```
http://127.0.0.1:8002/docs
```

---

## 💡 Project Background

This project is a reconstructed version of an academic banking application, redesigned using modern backend practices with REST APIs.

---

## 🔮 Future Improvements

* Authentication & authorization
* Transaction history tracking
* Web-based frontend dashboard
* Secure payment handling

---

## ⚠️ Note

This project focuses on backend design and API development rather than full production-level banking features.

git commit --allow-empty -m "refresh stats"
git push
