Documentation for TruckFlow Solutions Management System (TTMS)
Overview
The TruckFlow Solutions Management System (TTMS) is a Python-based application designed to streamline the operations of trucking and logistics businesses. With a responsive GUI, it offers robust functionality for managing drivers, trucks, orders, dispatches, accounts, and user roles. The system ensures secure, role-based access and provides tools for comprehensive analytics and reporting.

Features
1. User Management
Roles: Admin, Dispatcher, Accountant, Manager, and Driver.
Login System: Role-based authentication with a customizable login interface.
Admin Features: Ability to manage all modules and add new users.
2. Driver Management
Driver Records: Add, update, delete, and view driver details, including CNIC, license expiry, and contact information.
Salary Management: Record salary payments and generate monthly salary reports.
Compliance: Alerts for upcoming license expirations.
Driver Status Tracking: Monitor availability and trip history.
3. Truck Management
Truck Records: Add, update, delete, and view truck details, including model, status, and maintenance schedules.
Fleet Tracking: Monitor truck status (operational, under maintenance, retired).
Odometer Tracking: Automatic maintenance alerts when odometer thresholds are met.
4. Order Management
Order Records: Add, update, delete, and view order details, including customer name, pickup location, destination, weight, and payment status.
Order Allocation: Assign drivers and trucks to specific orders.
5. Dispatch Management
Dispatch Records: Manage dispatch details, including allocated trucks and drivers.
Real-Time Updates: Track estimated delivery times and dispatch statuses.
6. Financial Management
Transaction History: Record income and expenses, including fuel and maintenance costs.
Billing System: Generate invoices and payment receipts.
Analytics: Generate financial reports and visualize expenses.
7. Analytics and Reporting
Reports: Generate reports for fleet usage, driver performance, and financials.
Dashboard: Real-time analytics for management.
8. Notifications
Compliance Alerts: License expiry notifications for drivers.
Maintenance Alerts: Reminders for truck servicing based on odometer readings.
9. Security and Accessibility
Database Integration: Uses SQLite for secure, local storage of records.
Role-Based Access: Ensures data privacy with user-specific dashboards.
Responsive GUI: Adapts to different screen resolutions.
Installation
Prerequisites:

Python 3.8 or higher.
Required libraries:
java
Copy code
tkinter
sqlite3
openpyxl
matplotlib
tkcalendar
PIL (Pillow)
ttkthemes
Install dependencies using pip:
Copy code
pip install matplotlib tkcalendar Pillow ttkthemes
Database Initialization:

The database (TTMS.db) is created automatically upon running the program. Ensure the script has write access to the directory.
Running the Application:

Execute the script:
Copy code
python TTMS.py
Usage Instructions
Login
Launch the application.
Enter the username and password.
Depending on the role, you will be redirected to the respective dashboard.
Admin Dashboard
Access all system modules.
Manage users and monitor operations.
Driver Management
Navigate to the "Manage Drivers" section.
Add new drivers, update their details, or delete records.
Generate salary reports or view compliance alerts.
Truck Management
Navigate to the "Manage Trucks" section.
Add new trucks, update maintenance records, and monitor fleet usage.
Track fuel and maintenance expenses.
Order Management
Navigate to the "Manage Orders" section.
Create and manage customer orders.
Assign trucks and drivers to dispatch orders.
Dispatch Management
Navigate to the "Manage Dispatch" section.
Track real-time dispatch updates and estimated delivery times.
Financial Management
Navigate to the "Manage Accounts" section.
Record payments, track expenses, and generate invoices.
Customization
Themes: Modify the application's theme using the ttkthemes library.
Database Path: Change the database location by updating DATABASE_PATH in the script.
Known Issues
None reported.
Support
For issues, contact TruckFlow Solutions:

Email: chsajjadshahid@outlook.com
Phone: (+92) 333-5130-796
