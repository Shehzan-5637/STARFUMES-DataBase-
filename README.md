# STARFUMES-OnlineStore
SQL-based Online Store Management System for a perfume retail business with automated inventory, orders, and payment tracking.
🌸 STARFUMES – Online Store Management System

A SQL-based Online Store Management System for STARFUMES, a perfume retail business. The system automates inventory, order processing, and payment tracking, while providing reporting for management.

🚀 Features
🆕 Customer Management: Store customer information and addresses.
💰 Order Processing: Place orders with multiple items.
📦 Inventory Control: Automatic stock updates; prevent overselling.
💳 Payment Tracking: Record payments and auto-confirm orders after payment.
📊 Reporting & Views:
Daily Sales
Customer Order History
Pending Payments
Low Stock Alerts
🧪 Technologies Used
Component	Technology
Database	Microsoft SQL Server
Logic	SQL (Tables, Triggers, Views)
Reporting	SQL Views
Platform	Windows / Linux (SQL Server compatible)
🗂️ Project Structure
STARFUMES-OnlineStore/
├── README.md                 # Project documentation
├── LICENSE                   # MIT License
├── SQL/
│   ├── 01_create_tables.sql  # Create database & tables
│   ├── 02_insert_data.sql    # Sample data insertion
│   ├── 03_triggers.sql       # Business logic triggers
│   ├── 04_views.sql          # Reporting views
│   └── 05_queries.sql        # Sample queries / testing
├── Screenshots/              # Query output screenshots
├── ERD/
│   └── er_diagram.png        # ER Diagram
└── Documentation/
    └── STARFUMES_Report.pdf # Lab report
▶️ How to Run
Open SQL Server Management Studio (SSMS).
Execute scripts in order:
01_create_tables.sql
02_insert_data.sql
03_triggers.sql
04_views.sql
05_queries.sql
Verify outputs via the Screenshots folder.
📤 Sample Output

Customer Order History:

CustomerName | OrderID | Perfume | Quantity | Status
Faizan Punjwani | 1 | Sirius Essence | 2 | Confirmed

Daily Sales:

Order Date  | TotalSales
2025-11-01  | 7100

Pending Payments:

OrderID | CustomerName | Amount | Payment Method | Status
2       | Yusra Habib  | 5000   | Cash on Delivery | Pending

Low Stock Perfumes:

Perfume Name      | Stock
Sirius Essence    | 4
📁 Data Format

Customers1 table:

customer_id,name,address
1,Faizan Punjwani,Karachi
2,Yusra Habib,Islamabad

Perfumes1 table:

perfume_id,perfume_name,price,stock
1,Sirius Essence,3500,20
2,Vega Bloom,3200,18

Orders1 table:

order_id,customer_id,order_date,status,shipping_address
1,1,2025-11-01,Confirmed,Karachi

OrderItems1 table:

item_id,order_id,perfume_id,quantity
1,1,1,2

Payments1 table:

payment_id,order_id,amount,payment_method,payment_status
1,1,7100,Bank Transfer,Completed
📚 Learning Objectives
Relational database design & normalization
SQL triggers for business logic automation
Reporting with SQL views
Data integrity and real-time stock management
Practical database management for retail operations
📫 Contact

Ali Shehzan Punjwani 
🎓 BSCS Student @ Iqra University
📍 Karachi, Pakistan
📧 shehzansohail5637@gmail.com
🔗 www.linkedin.com/in/ali-shehzan-punjwani
