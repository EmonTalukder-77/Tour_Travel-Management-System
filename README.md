

---


#  GoPlan 🌍Tour_Travel Management System


## Overview


**GoPlan Tour** is a web-based travel management system built with **PHP and MySQL**.
It provides users with a platform to **explore travel packages, book tours, manage profiles, track bookings and offer a customize tour package** , while administrators can manage packages, bookings, enquiries, and users from a secure admin panel.


The system was developed as part of an academic project to demonstrate **database-driven web application development**.


---


##  Features


### User Side


*  Browse travel packages with details and images.
*  Make enquiries about travel packages.
*  Book packages online.
*  View booking history.
*  User authentication (Signup/Login).
*  Manage profile and change password.
*  **Customize your own package** (select transport, features, and members).


###  Admin Side


*  Create, edit, and update travel packages.
*  Manage registered users.
*  Manage enquiries and complaints.
*  Manage CMS pages (About, Contact, etc.).
*  Dashboard with booking stats.
*  Admin authentication with password recovery.


---


##  Special Highlight: Customize Your Package


One of the **main focuses of GoPlan Tour** is the **Customize Package module**, where users can create a fully personalized package instead of choosing from pre-defined ones.


The customization process includes:


1. **Package Name** – Give your package a unique name.
2. **Booking Type** – Select booking category (Transport).
3. **Transport Options** – Choose how you want to travel:


   *  Bus
   *  Car
   *  Train
   *  Plane
4. **Features** – Add optional features (meals, hotel, guide, insurance, etc.).
5. **Members** – Define how many people are included in the package.


This feature ensures users have **flexibility and control** over their travel experience, making the system more **personalized and user-centric**.


---


##  Project Structure


```
GoPlan_Tour/
│── tms/
│   ├── admin/                 # Admin Panel
│   │   ├── create-package.php
│   │   ├── manage-packages.php
│   │   ├── manage-users.php
│   │   ├── manage-bookings.php
│   │   ├── profile.php
│   │   └── ...  
│   ├── css/                   # Stylesheets
│   ├── js/                    # JavaScript files
│   ├── images/                # Project images
│   ├── includes/              # Reusable components (header, footer, db config)
│   ├── index.php              # Homepage
│   ├── package-details.php    # Package detail page
│   ├── enquiry.php            # User enquiry form
│   ├── profile.php            # User profile
│   └── ...  
```


---


##  Installation & Configuration
###  Step 1: Download & Setup


Download and extract the project zip file on your local system.


Copy the tms folder into your server’s root directory:


XAMPP → xampp/htdocs/


WAMP → wamp/www/


LAMP → var/www/html/


## 🗄 Step 2: Database Configuration


Open phpMyAdmin in your browser.


Create a new database named tms.


Import the provided SQL file tms.sql (available inside the project package).


##  Step 3: Run the Project


Open your browser and navigate to:


http://localhost/tms/


 Default Login Credentials
 Admin Panel


URL:


http://localhost/tms/admin




Username: admin


Password: 123456


 User Panel


URL: 
http://localhost/tms/


Email: emon@gmail.com 


Password: 123456










---



##  Future Enhancements


*  Online payment integration.
*  Email/SMS booking confirmation.
*  Advanced search and filter for packages.
*  Multi-language support.
*  Export customized packages as PDF.


---


##  Author


Developed by **Emon Talukder[221002357] & Md. Sabbir Hossain[21002309]** 

**GREEN UNIVERSITY OF BANGLADESH**


*  Contact: mail to  emontalukder@gmail.com & gub.sabbir@gmail.com
*  GitHub: (https://github.com/SabbirShadows)





