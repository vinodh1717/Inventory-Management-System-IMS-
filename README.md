# 🗃️ Inventory Management System (IMS)

A simple inventory management system built using Flask and SQLite. Users can register, log in, and manage their inventory. Items with quantity ≤ 5 trigger a low-stock alert on the dashboard.

## 🚀 Features

- User authentication (Register/Login)
- Add, edit, and delete inventory items
- Track item quantity, category, price & description
- Low-stock alert for items with quantity ≤ 5
- Highlights low-stock items in the table
- Flash messages for actions (add, update, delete)
- Clean UI with Bootstrap

## 💻 Tech Stack

- Python
- Flask
- SQLite (can be changed to MySQL)
- Flask-Login
- SQLAlchemy
- HTML + Bootstrap

## 📷 Screenshot

> Add a screenshot of your app's dashboard here if you have one

## ⚙️ How to Run

1. **Clone the repo**  
   ```bash
   git clone https://github.com/vinodh1717/Inventory-Management-System-IMS-.git
   cd Inventory-Management-System-IMS-
Create a virtual environment (optional but recommended)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install the required dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the app

bash
Copy
Edit
python app.py
Open in browser
Visit http://localhost:5000 to access the app.

thankyou

