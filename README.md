# Hotel-Management-System
It is a comprehensive Java-based desktop application designed to automate and streamline key hotel operations. This system simplifies tasks such as room booking, customer registration, check-in/check-out, and billing, all through an intuitive graphical user interface (GUI) built with Java Swing.


*INTRODUCTION
This Java-based Hotel Management System automates key operations in hotel administration, offering modules for room and customer management, employee handling, check-in/check-out processing, billing, and departmental tasks. Built with modular Java classes, the application features a graphical user interface (GUI), enabling hotel staff to efficiently manage diverse responsibilities and improve service quality.

*FEATURES
~ Room Booking and Management: Add, search, update, and manage room records.

~ Customer Registration & Details: Handle new and returning guests, store profiles, and manage customer data.

~ Check-In/Check-Out System: Guest arrival and departure processes.

~ Employee and Driver Management: Add, and update employee and driver information.

~ Departmental Management: Support backend hotel departments.

~ Reception Dashboard: Central hub for key hotel functions and services.

~ Manager Information Handling: Manage data for hotel managers and administrators.

~ Bill Calculation and Updating: Automate and update customer billing upon check-out.

~ Login & Authentication: Secure access for staff and managers.

~ Pick-Up & Support: Coordinate guest pick-up services.

* TECH USED
> Programming Language: Java

> GUI Framework: Java Swing

> Database: MySQL 

> IDE: Eclipse

* DETAILED PROJECT STRUCTURE:
AddDrivers.java: Enables addition and management of driver records for guest transport.
AddEmployee.java: Handles staff registration, data entry, and editing.
AddRoom.java: Facilitates addition of new rooms, including room type, price, and status.
CheckOut.java: Manages check-out workflow, bill updates, and customer departure.
conn.java: Provides database connectivity and query handling for persistent data storage.
CustomerInfo.java: Stores and displays detailed customer information; supports queries and reporting.
Dashboard.java: Offers an overview interface for navigating the system's main features.
Department.java: Manages hotel department listings and details, supporting backend administration.
HotelManagementSystem.java: Acts as the main entry point and controller for the integrated GUI application.
Login.java: Implements staff authentication and session management.
ManagerInfo.java: Handles manager profiles and administrative access rights.
NewCustomer.java: Registers guests and initiates their booking journey.
PickUp.java: Arranges and tracks pick-up logistics for guest arrivals.
Reception.java: Central module for front desk operations, handling queries, bookings, and guest support.
Room.java: Defines room properties, maintains status, and interfaces with booking and update modules.
SearchRoom.java: Enables room search functionality (by availability, type, etc.).
UpdateCheck.java: Updates customer information and check-in status post-booking.
UpdateRoom.java: Manages changes to room status/details (maintenance, pricing, etc.).


Authentication: Start with Login.java for secure access.

Reception Operations: Use Reception.java and Dashboard.java to manage customer bookings, check-ins, and queries.

Room and Customer Management: Register rooms and customers through AddRoom.java and NewCustomer.java, update using corresponding update classes.

Department & Staff: Administer hotel staff via AddEmployee.java, ManagerInfo.java, and Department.java.

Check-Out & Billing: Use CheckOut.java and UpdateCheck.java for departure handling and bill updates.

Transport & Support: Manage guest pick-up and driver scheduling using AddDrivers.java and PickUp.java.

 THANK YOU😊
