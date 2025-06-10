# Grocery-Store-Application
Grocery Store Management Web Application
This is a full-stack grocery store management application built using a 3-tier architecture.

Frontend: HTML, CSS, JavaScript, Bootstrap

Backend: Python with Flask

Database: MySQL

Features
View, add, edit, and delete products

Place and manage customer orders

Track unit of measurement (UOM) for inventory items

Dynamic total price calculation and order summaries

Installation Instructions
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/Grocery-Store-Application.git
cd Grocery-Store-Application

2. Install MySQL
Download and install MySQL from the official site:
https://dev.mysql.com/downloads/installer/

3. Install Required Python Packages
bash
Copy
Edit
pip install mysql-connector-python
pip install flask
4. Configure Database
Create a MySQL database (e.g., grocery_store)

Update database credentials in the backend configuration file (usually app.py or config.py)
![image](https://github.com/user-attachments/assets/f1c52c1b-97e5-44aa-84c5-1a17db84b6a5)


Exercise & Feature Enhancements
After testing with users, here’s the feedback and tasks implemented:

Products Module
 Edit Product: Added an "Edit" button next to "Delete" to update product details.

 Add UOM: Implemented a new form to add units of measurement (e.g., Cubic Meter) — updated both backend and frontend.

 Orders Module
 Input Validation: Added frontend validations:

Customer name must not be empty

Quantity must be a positive number

Invalid item names are flagged

 Price Calculation Bug Fix: Fixed bug where changing an item's total price manually didn’t update the grand total.

 Order Details View: Added a “View” button to see individual order details (item name, quantity, unit price, total, etc.)


 Feedback & Contributions
Have suggestions or want to contribute? Feel free to open an Issue or submit a Pull Request!

