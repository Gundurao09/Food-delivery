# 🍔 Food-delivery API
A FastAPI-based RESTful API for managing food delivery orders with features like status tracking, cancellation reasons, and summary insights. This service uses an in-memory data store and includes thread-safety for concurrent access.


## 🚀 Features
- Create new orders
- View list of all orders
- Get order details by ID
- Update order status (including cancellation with reason)
- View summary statistics (total orders and total amount)
- Thread-safe in-memory order storage (no database required)

## 📦 Setup Instructions
### 1. Clone the repository
- git clone [(https://github.com/Gundurao09/Food-delivery/)]
  
### 2. Create and activate a virtual environment
- python -m venv venv
- macOS/Linux: source venv/bin/activate
- Windows: venv\Scripts\activate

### 3. Install required packages
- pip install -r requirements.txt
##### If you don’t have a requirements.txt file, create one with the following content:
- fastapi
- uvicorn
- pydantic

## 🟢 Running the API Server
- uvicorn main:app --reload
* Replace main with your Python filename (without .py)
* The --reload option automatically restarts the server on code changes.
