# Transportation_management_syste.
﻿To run this application, you'll need to install the required Python packages and set up your SQL Server database:

1. Install required Python packages:
   ```
   pip install tkinter pyodbc
   ```


2. Set up your SQL Server database:
   - Open SQL Server Management Studio (SSMS)
   - Connect to your SQL Server instance
   - Run the SQL script provided in the "Transport System Database Schema" artifact to create the database and tables


3. Configure the database connection:
   - Update the connection details in the `connect_to_database()` method of the TransportApp class:
     - Server name
     - Username
     - Password


4. Run the application:
   ```
   python transport_app.py
   ```


Features of the Application


The application includes the following features:


1. Vehicle Management:
   - Add, edit, delete, and view vehicles
   - Track vehicle type, registration, capacity, and status


2. Route Management:
   - Define transport routes with start/end locations
   - Track distance and duration


3. Driver Management:
   - Manage driver information and availability
   - Track license and contact information


4. Booking System:
   - Schedule transport services
   - Assign vehicles and drivers to routes
   - Track booking status
   - 
