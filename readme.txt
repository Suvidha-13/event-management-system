# Event Management System using PHP/MySQL

## About

The Event Management System is a PHP/MySQL project designed to assist event organizing companies in efficiently managing client event details and marketing their events and venue lists. This system allows potential event audiences to register online through the company's website. Audience registrations are treated as requests initially, and the system admin or management can follow up with the audience to verify their registration for the event and handle payments if necessary. The system also provides a platform for clients to inquire about desired venues for their events.

On the admin side, the system offers dynamic venue lists, which can be easily managed and displayed on the website. Admins or staff can populate the list of events the company handles, along with all the relevant details and descriptions for public display. The company can choose to publish certain events on the website for potential audience registration and market them online. Alternatively, the company can keep event details private and use the system to maintain an internal event list for reporting purposes.

The Event Management System also supports the storage of venue images, event banners, and other essential details, further assisting clients in promoting their events and venues effectively.

## Features

### Management Side

- **Login Page:** Users can securely access the event management system by providing their credentials.
- **Home Page:** After logging in, users are redirected to the home page, providing an overview of their tasks.
- **Venues Page:** Event organizing company's venues are listed and managed on this page.
- **Events Page:** The system allows easy management of the events the company handles.
- **Venue Book List:** This page displays and manages online booking inquiries for venues.
- **Event Audience List:** Potential audience members who submitted registration requests using the website are listed and managed here.
- **Audience Report:** Organized by events, this page lists all registered audience members and can be printed for reference.
- **Venue Report:** Organized by venue and month, this page lists all events in a particular venue and can be printed for reference.
- **Users Page:** System administrators can manage user accounts on this page.
- **System Settings:** This page enables system administrators to manage the company details displayed on the website.

### Visitor Side

- **Home Page:** The default landing page for visitors, showcasing upcoming events.
- **Venues Page:** Visitors can explore the event organizing company's available venues.
- **About Page:** This page provides insights into the event organizing company and its mission.

## Installation

1. Download and install XAMPP Server from [here](https://www.apachefriends.org/download.html).
2. Ensure you have a text editor installed for code modifications.
3. Start Apache and MySQL on XAMPP Server.
4. Go to http://localhost/phpmyadmin and create a database named "event_db".
5. Import the event_db.sql file into the database.
6. After a successful import, place the project folder into C:\xampp\htdocs.
7. Open the link: http://localhost/event-management-system to access the website.
8. For admin access, go to: http://localhost/event-management-system/admin/login.php

   **LOGIN DETAILS**  
   **Admin**  
   User: admin  
   Pass: admin123

