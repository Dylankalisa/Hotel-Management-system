

Hotel Management System (HMS)
Project Overview
The Hotel Management System (HMS) is designed to streamline hotel operations by automating key processes such as room reservations, check-ins, room service, and billing. The system improves efficiency, enhances guest experience, and ensures high security and performance.
Features
Functional Requirements
Room Reservation: Guests can book rooms online or at the reception with real-time availability updates.
Check-in/Check-out: Fast processing at the front desk to improve customer experience.
Room Service & Billing: Guests can order services, and charges are automatically added to their account.
Inventory Management: Tracks room status, maintenance needs, and amenities like mini-bar stock.
User Management: Role-based access control for security and operational efficiency.
Reporting: Provides analytical reports on hotel occupancy, revenue, and service usage.
Non-Functional Requirements
Security: Protects guest and financial data with encryption and access control.
Performance: Handles peak loads efficiently.
Usability: User-friendly interface for both staff and guests.
Scalability: Can accommodate hotel expansion and additional services.
Reliability: Ensures 24/7 availability with minimal downtime.
System Users
Guests: Individuals or groups who book rooms and use hotel services.
Hotel Staff: Receptionists, housekeepers, and maintenance personnel who manage daily operations.
Administrators: Oversee the system, manage users, and generate reports.
Class Design
The system follows an object-oriented approach with the following key classes:
User (Abstract Class) → Extended by Guest, Staff, Manager, and Administrator.
Room: Stores room details (room number, type, and status).
Reservation: Manages room reservations and is linked to both Room and Guest.
Service: Handles room service requests.
Billing: Manages financial transactions, service charges, and payments.
Inventory: Keeps track of room availability and amenities like mini-bar stock.
Technologies Used
Programming Language: Java
Database: MySQL (or any relational database for persistence)
Development Tools: IntelliJ IDEA, Eclipse, NetBeans
Version Control: Git
Installation & Setup
Clone the repository:
 git clone https://github.com/your-repo/hotel-management-system.git
cd hotel-management-system


Compile and run the project:
 javac Main.java
java Main


(Optional) Set up a database connection in config.properties if using MySQL.
Future Enhancements
Add a Graphical User Interface (GUI) for better usability.
Implement an online booking system with web or mobile integration.
Integrate AI-powered analytics for better business insights.
Enhance security with multi-factor authentication for staff and administrators.
Contributors
Kalisa Newport Dylan
Open for contributions! Feel free to submit pull requests.

