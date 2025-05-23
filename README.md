# Food-delivery

A FastAPI-based RESTful service for managing orders with features like status updates and cancellation history.

---

## 🚀 Features

- Create new orders
- View list of all orders
- Get order details by ID
- Update order status (e.g., cancel with reason)
- View order summary (count and total amount)
- Thread-safe in-memory storage with optional JSON persistence

---

## 📦 Requirements

- Python 3.8 or higher
- FastAPI
- Uvicorn
- Pydantic

---

## 🐍 Create and Activate Virtual Environment

```bash
# Create a virtual environment named 'venv'
python -m venv venv

# Activate on macOS/Linux
source venv/bin/activate

# Activate on Windows
venv\Scripts\activate


## Then install required packages:
pip install fastapi uvicorn

## 🚀 2. Running the API Server
uvicorn main:app --reload

---

## 🛠️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/your-username/order-management-api.git
cd order-management-api

main: Replace with your Python filename (without .py).

--reload: Automatically reloads the server on code changes.



