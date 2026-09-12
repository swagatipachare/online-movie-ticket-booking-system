🎬 Online Movie Ticket Booking System

A web-based Online Movie Ticket Booking System developed using
PHP, MySQL, HTML, CSS, Bootstrap, and JavaScript.

The system is designed to make movie ticket booking easier by allowing
users to register/login, browse movies and showtimes, check seat
availability, select seats, make bookings/payments, and manage tickets.
An admin module is included for managing movies, theatres, screens,
schedules, users, tickets, and payments.

Project: Online Movie Ticket Booking System
Backend: PHP + MySQL
Frontend: HTML + CSS + Bootstrap + JavaScript

🌐 Live Demo

Live URL: To be added after deployment

The project can be deployed to a PHP + MySQL hosting provider. For this
existing PHP/MySQL project, a PHP/MySQL shared host is the simplest
deployment option.

✨ Features

👤 User Module

User registration

User login

Browse movie information

View showtimes

Check seat availability

Select seats

Book movie tickets

Payment/checkout flow

Ticket confirmation

Ticket printing/saving

Ticket cancellation

Booking history

Feedback/support functionality

🔐 Admin Module

Admin login

Admin dashboard

Manage movies

Manage theatres

Manage screens

Manage show schedules

Manage bookings

Manage tickets

Manage users

Manage payments

Manage movie/news information

View reports

🎟️ Booking

Movie selection

Theatre/screen selection

Showtime selection

Seat availability

Ticket quantity

Price calculation

Booking reference/ticket details

🛠️ Technology Stack

Layer                   Technology

Frontend                HTML5
Styling                 CSS3
UI Framework            Bootstrap
Client-side scripting   JavaScript
Backend                 PHP
Database                MySQL
Local Server            XAMPP / Apache
Database Management     phpMyAdmin

The project report specifies HTML, CSS, Bootstrap and JavaScript for the
frontend and PHP/MySQL for the backend.

🏗️ System Modules

Online Movie Ticket Booking System
│
├── User Module
│   ├── Registration
│   ├── Login
│   ├── Movie Selection
│   ├── Showtime
│   ├── Seat Availability
│   ├── Booking
│   ├── Payment
│   ├── Ticket
│   └── Cancellation
│
└── Admin Module
    ├── Dashboard
    ├── Movie Management
    ├── Theatre Management
    ├── Screen Management
    ├── Show Management
    ├── Booking Management
    ├── Ticket Management
    ├── User Management
    └── Payment Management

🗄️ Database

The project documentation describes tables including:

Login

Registration

Movie

Booking

News

Theatre

Screen

Shows

Showtime

Contact

The database stores information related to users, movies, theatres,
screens, shows, bookings, tickets, and payments.

💻 Run Locally

1. Install XAMPP

Install XAMPP and start:

Apache
MySQL

2. Copy the project

Copy the project folder into:

C:\xampp\htdocs\

For example:

C:\xampp\htdocs\movie-booking\

3. Create the database

Open:

http://localhost/phpmyadmin

Create a MySQL database, for example:

movie_booking

Import the project's .sql database file into the database.

4. Configure database connection

Find the project's PHP database configuration file.

Typical configuration looks like:

$conn = mysqli_connect(
    "localhost",
    "root",
    "",
    "movie_booking"
);

Important: Use the actual database name, username, password, and
configuration file from the source code.

5. Run the application

Open:

http://localhost/movie-booking/

The exact URL depends on the project folder name.

🚀 Deployment

Recommended simple deployment: PHP + MySQL hosting

Because this project uses traditional PHP and MySQL, the easiest
deployment route is a hosting provider that directly supports PHP and
MySQL.

Deployment checklist

Before uploading:

[ ] PHP files
[ ] CSS files
[ ] JavaScript files
[ ] Images/assets
[ ] SQL database export
[ ] Database configuration updated
[ ] Admin credentials checked
[ ] Payment configuration checked

General deployment process

Create a PHP/MySQL hosting account.

Create a MySQL database.

Note the:

Database host

Database name

Database username

Database password

Import the project's .sql file.

Upload the complete project files.

Update the PHP database connection.

Check file/folder paths.

Open the generated HTTPS website URL.

Test registration and login.

Test movie selection.

Test seat selection.

Test booking.

Test admin login.

Test admin management pages.

🔒 Production Security Checklist

Before sharing the live URL publicly:

Do not upload database passwords to GitHub.

Change default admin credentials.

Use HTTPS.

Validate all user input.

Use prepared SQL statements.

Protect admin pages with authentication and authorization.

Do not store raw payment card information.

Keep PHP and dependencies updated.

Disable unnecessary debug/error output on production.

Take regular database backups.

📱 Main User Flow

Register
   ↓
Login
   ↓
Browse Movies
   ↓
Select Movie
   ↓
Select Theatre / Screen
   ↓
Select Showtime
   ↓
Check Seat Availability
   ↓
Select Seats
   ↓
Calculate Price
   ↓
Payment / Checkout
   ↓
Booking Confirmation
   ↓
Print / Save Ticket

🔐 Admin Flow

Admin Login
    ↓
Admin Dashboard
    ↓
Manage Movies
    ↓
Manage Theatres
    ↓
Manage Screens
    ↓
Manage Shows / Showtimes
    ↓
Manage Bookings
    ↓
Manage Tickets
    ↓
Manage Users
    ↓
Manage Payments

📸 Project Screens

The project documentation contains screenshots/diagrams for pages such
as:

Registration

Login

Payment

Admin login

Home page

Movie selection

Theatre selection

Admin theatre management

Screen management

Add your final screenshots here after deployment:

screenshots/
├── home.png
├── login.png
├── registration.png
├── movies.png
├── seat-selection.png
├── payment.png
├── ticket.png
└── admin-dashboard.png

Example:

![Home Page](screenshots/home.png)

📊 System Design

The project documentation includes:

System flow diagram

Data Flow Diagram (DFD)

Entity Relationship Diagram (ERD)

Database table design

User and Admin module descriptions

The documented system flow separates users and administrators after
login. Users can view movie information, check availability, book/cancel
tickets and make payments, while administrators manage movies, screens,
schedules, tickets, users and payments.

🧪 Testing

Test the following before deployment:

Test                       Status

User Registration          ⬜
User Login                 ⬜
Admin Login                ⬜
Movie Listing              ⬜
Movie Selection            ⬜
Showtime Selection         ⬜
Seat Availability          ⬜
Seat Selection             ⬜
Booking                    ⬜
Payment                    ⬜
Ticket Confirmation        ⬜
Ticket Cancellation        ⬜
Booking History            ⬜
Admin Movie Management     ⬜
Admin Theatre Management   ⬜
Admin Screen Management    ⬜

🔮 Future Enhancements

Possible future improvements include:

Dedicated Android/iOS application

QR-code/NFC ticket validation

Personalized movie recommendations

AI/ML recommendation engine

Chatbot/voice assistant

Social media integration

Improved mobile responsiveness

Advanced analytics

Push notifications

Better payment-gateway integration

AR/VR-based theatre seat visualization

⚠️ Limitations

The project documentation identifies areas that may require additional
work for a production-scale system, including scalability, performance
optimization, security, third-party compatibility, complex business
rules, mobile responsiveness, and ongoing maintenance.

👩‍💻 Project Information

Project Title: Online Movie Ticket Booking System

Developed by: - Swagati K. Pachare - Dikshita P. Sahare

Course: Master of Computer Applications (MCA)

Technology: PHP + MySQL + HTML + CSS + Bootstrap + JavaScript

Academic Project: VMV Commerce, JMT Arts & JJP Science College,
Nagpur

📄 Documentation

The complete academic project report contains the project introduction,
problem definition, system analysis/design, DFD, ERD, table design,
implementation/results, testing, user manual, conclusion, limitations,
and future scope.

⭐ GitHub Repository

After uploading the source code to GitHub, replace this section with:

Repository:
https://github.com/YOUR-USERNAME/movie-ticket-booking-system

🌐 Live Project

After deployment, replace the placeholder below:

Live Demo:
https://YOUR-LIVE-DOMAIN/

📌 Deployment Note

The README describes deployment requirements based on the project
report. The actual database name, PHP configuration filename, folder
structure, admin credentials, SQL dump filename, and payment
configuration must be taken from the source-code project, not
inferred from the academic report.
