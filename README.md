**🧾 Project Title: INVENTORY MANAGEMENT**

**1️⃣ Problem Statement**

Currently, there is no automated system to insert, manage, and display product details efficiently. When inserting a new product, ID generation and stock management must be handled manually, which can lead to inconsistencies, duplicate IDs, and outdated stock information. The project aims to automate this process to ensure smooth product entry, tracking, and availability display.

**2️⃣ Objectives**

Automate the process of product insertion with unique ID generation.
Ensure data consistency and accuracy during insertion.
Automatically update stock availability after new product entries.
Display reports and summaries for easy monitoring.

**3️⃣ Functional Requirements**

A. Product Insertion
A new product should be inserted using a stored procedure.
Each product must have a unique Product ID, which should be auto-generated sequentially (e.g., S101, S102, etc.).
After insertion, product details such as name, category, supplier, cost, and quantity should be stored in the database.
The stock should be automatically updated after each insertion.

B. Stock Management
When a new product is added, its stock quantity should be reflected automatically in the stock table.
The availability status (e.g., “Available”, “Out of Stock”) should depend on the stock quantity.
The system should allow updating stock when additional items are received or products are sold.

C. Display & Reports
Provide a display page or report to view all product details.
Reports should include:
Product name
Supplier name
Cost and quantity
Availability status
Allow filtering and searching based on supplier, category, or availability.

D. Integration & Flow
All modules (product insertion, stock update, and display) should be interconnected.
Any product inserted using the procedure should automatically be visible in the display/report section.
