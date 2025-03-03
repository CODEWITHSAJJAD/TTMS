**TruckFlow Solutions - Transport Management System (TTMS)
TruckFlow Solutions is a comprehensive Transport Management System (TTMS) designed to streamline and automate the operations of logistics and transportation companies. This system provides a centralized platform for managing various aspects of transportation operations, including driver management, truck management, order management, dispatch management, financial management, and reporting. The system is built using Python with a Tkinter-based GUI for a user-friendly interface and  OpenPyXL  for Excel-based data storage and SQL for DATABASE storage.The system is role-based, allowing different users (Admin, Manager, Dispatcher, Accountant, and Driver) to access specific modules based on their responsibilities. Below is a detailed explanation of each module and its functionality:
---

### 1. **Login Module**

  - **Purpose**: Authenticates users and redirects them to their respective dashboards based on their roles.

  - **Features**:

   - Secure login with username and password.

   - Role-based access control (Admin, Manager, Dispatcher, Accountant, Driver).

   - Default admin account for initial setup.

  - **Workflow**:

   - Users enter their credentials.

   - The system verifies the credentials against the "Users" sheet in the Excel workbook and same for SQL approach.

   - Upon successful authentication, users are redirected to their respective dashboards.

---

### 2. **Admin Dashboard**

  - **Purpose**: Provides the admin with access to all system modules.

  - **Features**:

   - Access to **Driver Management**, **Truck Management**, **Order Management**, **Dispatch Management**, **Financial Management**, **Reports**, and **User Management**.

   - Real-time clock display.

   - Logout functionality.

  - **Workflow**:

   - Admin can navigate to different modules using the dashboard buttons.

   - Each module opens in a new window, allowing the admin to manage specific aspects of the system.

---

### 3. **Driver Management Module**

  - **Purpose**: Manages driver information, salary, leave, and compliance.

  - **Features**:

   - Add, update, and delete driver records.

   - Track driver salary payments and leave requests.

   - Check driver license expiry and compliance.

   - Generate salary reports and track driver performance.

  - **Workflow**:

   - Admin/Manager can add new drivers with details like name, CNIC, contact, salary, and license expiry.

   - Track salary payments and update driver status (Available, On Trip, Off Duty).

   - Manage driver leave requests (Sick Leave, Annual Leave, Emergency Leave).

   - Generate monthly salary reports and track driver performance metrics.

---

### 4. **Truck Management Module**

  - **Purpose**: Manages truck information, maintenance, and fuel expenses.

  - **Features**:

   - Add, update, and delete truck records.

   - Track truck maintenance schedules and expenses.

   - Record fuel expenses and update odometer readings.

   - Generate maintenance reports and check truck compatibility for orders.

  - **Workflow**:

   - Admin/Manager can add new trucks with details like model, status, permit, and weight capacity.

   - Record maintenance expenses and fuel consumption.

   - Update odometer readings and check for upcoming maintenance.

   - Generate maintenance and fuel expense reports.

---

### 5. **Order Management Module**

  - **Purpose**: Manages customer orders, payments, and order status.

  - **Features**:

   - Add, update, and delete order records.

   - Track order status (Pending, In Transit, Delivered, Cancelled).

   - Calculate order totals with GST.

   - Record payments and generate invoices.

   - Export order data to Excel and PDF.

  - **Workflow**:

   - Admin/Manager/Dispatcher can create new orders with details like customer name, pickup, destination, weight, and GST.

   - Track order payments and update payment status (Pending, Partial, Completed).

   - Generate invoices and export order data for reporting.

---

### 6. **Dispatch Management Module**

  - **Purpose**: Manages the dispatch of trucks and drivers for orders.

  - **Features**:

   - Assign drivers and trucks to orders.

   - Track dispatch status (In Transit, Out for Delivery, Delivered).

   - Update estimated delivery times.

   - Check driver and truck availability.

   - Check order origin and truck permit.

   - Generate dispatch reports and export data.

  - **Workflow**:

   - Dispatcher assigns available drivers and trucks to pending orders.

   - Track the progress of dispatches and update status.

   - Generate dispatch reports and export data to Excel, CSV, or PDF.

---

### 7. **Financial Management Module**

  - **Purpose**: Manages financial transactions, expenses, and payments.

  - **Features**:

   - Record expenses (Fuel, Maintenance, Salary, Insurance, Other).

   - Record order payments and update payment status.

   - Track total payments, expenses, and balance.

   - Generate financial reports and export data to PDF.

  - **Workflow**:

   - Accountant records expenses and payments.

   - Track financial transactions and generate reports.

   - Export financial data to PDF for accounting purposes.

---

### 8. **Reports and Analytics Module**

  - **Purpose**: Provides detailed reports and analytics for better decision-making.

  - **Features**:

   - Generate salary reports for drivers.

   - Generate maintenance and fuel expense reports for trucks.

   - Generate financial reports for payments and expenses.

   - Export reports to Excel, CSV, and PDF.

  - **Workflow**:

   - Admin/Manager/Accountant can generate reports based on specific criteria (e.g., date range, type).

   - Export reports for further analysis or sharing.

---

### 9. **User Management Module**

  - **Purpose**: Manages user accounts and roles.

  - **Features**:

   - Add, update, and delete user accounts.

   - Assign roles (Admin, Manager, Dispatcher, Accountant, Driver).

   - Reset passwords and update user information.

  - **Workflow**:

   - Admin can create new user accounts and assign roles.

   - Update user information and reset passwords as needed.

---

### 10. **Backup and Export Module**

  - **Purpose**: Ensures data safety and allows data export for external use.

  - **Features**:

   - Backup the entire database to a separate Excel file.

   - Export data (orders, dispatches, financials) to Excel, CSV, and PDF.

  - **Workflow**:

   - Admin can create backups of the database to prevent data loss.

   - Export data for external reporting or analysis.

---

### 11. **Leave Management Module**

  - **Purpose**: Manages driver leave requests and approvals.

  - **Features**:

   - Submit leave requests (Sick Leave, Annual Leave, Emergency Leave).

   - Approve or reject leave requests.

   - Track leave history and driver availability.

  - **Workflow**:

   - Drivers submit leave requests through the system.

   - Admin/Manager approves or rejects leave requests.

   - Track leave history and update driver status accordingly.

---

### 12. **Performance Tracking Module**

  - **Purpose**: Tracks driver and truck performance metrics.

  - **Features**:

   - Calculate driver performance based on trips and on-time deliveries.

   - Track truck performance based on maintenance and fuel efficiency.

   - Generate performance reports.

  - **Workflow**:

   - System calculates performance metrics based on historical data.

   - Admin/Manager can view performance reports and make informed decisions.

---

### 13. **Compliance and Alerts Module**

  - **Purpose**: Ensures compliance with regulations and sends alerts for important events.

  - **Features**:

   - Check driver license expiry and send alerts.

   - Check truck maintenance schedules and send alerts.

   - Send alerts for unpaid salaries and pending orders.

  - **Workflow**:

   - System checks for compliance issues (e.g., expired licenses, overdue maintenance).

   - Sends alerts to the admin/manager for immediate action.

---

### 14. **Printing and Exporting Module**

  - **Purpose**: Allows users to print and export data for offline use.

  - **Features**:

   - Print order details, dispatch details, and financial transactions.

   - Export data to Excel, CSV, and PDF formats.

  - **Workflow**:

   - Users can print or export data directly from the system for offline use or sharing.

---

### 15. **Real-Time Updates and Notifications**

  - **Purpose**: Provides real-time updates and notifications for important events.

  - **Features**:

   - Real-time updates on order status, dispatch status, and financial transactions.

   - Notifications for upcoming maintenance, license expiry, and unpaid salaries.

  - **Workflow**:

   - System continuously monitors the database for important events.

   - Sends real-time notifications to the relevant users.

---

### Conclusion:

**TruckFlow Solutions - Transport Management System (TTMS)** is a robust and user-friendly system designed to streamline the operations of logistics and transportation companies. With its comprehensive modules, role-based access control, and real-time updates, TTMS ensures efficient management of drivers, trucks, orders, dispatches, and finances. The system's ability to generate detailed reports and export data makes it an invaluable tool for decision-making and compliance. Whether you're an admin, manager, dispatcher, or accountant, TTMS provides the tools you need to manage your transportation operations effectively.
