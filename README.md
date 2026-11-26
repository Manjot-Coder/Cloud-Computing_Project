PharmaCloud – Pharmacy Inventory Management System
A cloud-based web application designed to simplify pharmacy inventory management by providing centralized medicine records, stock tracking, expiry monitoring, low-stock alerts, supplier management, purchase tracking and inventory reports.

Overview
PharmaCloud is a web-based inventory management solution developed to help pharmacies organize and monitor their inventory efficiently. It provides an interactive dashboard and dedicated modules for managing medicine records, tracking stock movement, reviewing expiry information, organizing suppliers and purchases, and viewing inventory summaries.

The application uses React for its frontend and Firebase services for authentication, cloud database storage and web hosting.

Features
Dashboard: Overview of inventory information and key stock indicators.

Medicine Management: Manage and maintain medicine records.

Stock In: Record inventory additions.

Stock Out: Record inventory deductions.

Expiry Management: Review expiry-related inventory information.

Low Stock Alerts: Identify medicines requiring stock review or replenishment.

Supplier Management: Organize supplier records.

Purchase Management: Maintain purchase-related information.

Reports & Analytics: Review inventory summaries and available stock insights.

Cloud Integration: Cloud-based data storage using Firebase.

Web Hosting: Deploy and access the application through Firebase Hosting.

Tech Stack
Technology	Purpose
React	Frontend user interface
Firebase Authentication	User authentication
Cloud Firestore	Cloud database
Firebase Hosting	Web application hosting
JavaScript	Application logic
CSS	Styling and interface design
System Architecture
The application follows a frontend-and-cloud-services architecture.

             USER
              |
              v
       React Web Application
              |
       +------+------+
       |             |
       v             v
Firebase Auth    Cloud Firestore
                     |
                     v
             Inventory Records
The frontend interacts with Firebase services for authentication and database operations. Cloud Firestore stores application records, while Firebase Hosting can be used to deploy the frontend.

Application Modules
1. Dashboard
Displays inventory-oriented summaries, including medicine records, stock quantities, low-stock indicators and expiry-related information.

2. Medicines
Provides functionality for managing and reviewing medicine records.

3. Inventory
Supports stock-in and stock-out operations to maintain inventory quantities.

4. Expiry Management
Helps review medicines nearing expiry and expired inventory.

5. Alerts
Displays low-stock and expiry-related indicators for inventory review.

6. Suppliers
Maintains supplier-related information.

7. Purchases
Organizes purchase-related records.

8. Reports & Analytics
Provides inventory summaries and insights based on stored records.

Installation & Setup
Prerequisites
Node.js and npm

Firebase account

Git

1. Clone the Repository
git clone YOUR_REPOSITORY_URL
2. Navigate to the Project Directory
cd pharmacy-inventory
3. Install Dependencies
npm install
4. Configure Firebase
Create a Firebase project through the Firebase Console.

Configure the required Firebase services:

Firebase Authentication

Cloud Firestore

Firebase Hosting

Add your Firebase configuration to the application according to the project's Firebase configuration file.

5. Run the Application
npm run dev
Open the local URL provided by Vite in your browser.

Deployment
The application can be deployed using Firebase Hosting.

Build the Project
npm run build
Deploy to Firebase Hosting
firebase deploy --only hosting
After deployment, Firebase Hosting provides a live URL through which the application can be accessed.

Project Purpose
PharmaCloud aims to make pharmacy inventory operations more organized by providing a centralized platform for stock tracking, expiry review, supplier information, purchase records and inventory insights.

Future Enhancements
Barcode-based medicine scanning.

Automated email notifications.

Role-based access control.

Advanced analytics and demand forecasting.

Enhanced audit logs and backup functionality.

Disclaimer
PharmaCloud is an academic software project intended for inventory management and demonstration purposes. Inventory records should be verified, and the application should not be treated as a replacement for clinical judgement or pharmacy dispensing procedures.

Author
Computer Engineering Student Project

License
This project is developed for academic and educational purposes.
