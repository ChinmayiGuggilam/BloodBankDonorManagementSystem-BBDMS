# BloodBankDonorManagementSystem-BBDMS
A web-based platform developed in PHP and MySQL that streamlines the process of finding, registering, and managing blood donors and blood requests efficiently. 
BBDMS
│
├── admin/                  # Admin dashboard and management scripts
├── css/                   # Custom stylesheets
├── images/                # Website images and assets
├── includes/              # Reusable PHP components (header, footer, config)
├── js/                    # JavaScript files for UI effects and interactivity
├── webfonts/              # Font files used across the site
│
├── about.php              # About us page
├── change-password.php    # Change password functionality
├── contact.php            # General contact form
├── contact-blood.php      # Blood-specific contact/request
├── donor-list.php         # Public list of all donors
├── index.php              # Homepage
├── login.php              # User login page
├── logout.php             # User logout logic
├── profile.php            # Donor's profile page
├── request-received.php   # View of requests received
├── saerch-donar.php       # (Typo version) Search donor functionality
├── search-donor.php       # Correct version - search donor by blood group
├── sign-up.php            # Donor registration
💡 Features
📝 Donor Registration (via sign-up.php)

🔐 Login/Logout System (via login.php, logout.php)

👤 Donor Profile Management

🔍 Search Donors by blood group and location (search-donor.php)

📜 Donor List View for public visibility

📧 Contact Request for Blood Donation

🔁 Blood Request Received Management

🔒 Change Password functionality

📊 Admin Dashboard (inside /admin/)

📬 Contact Forms (general & blood-related)




1.Set Up the Database
Open phpMyAdmin: http://localhost/phpmyadmin

Create a new database:
bbdms and necessary tables

Open your browser and go to: http://localhost/project-folder


🖼️ Screenshots
<img width="1000" height="1000" alt="image" src="https://github.com/user-attachments/assets/68be27d1-36f0-4f67-8ad4-fc8cc74d5ee6" />
<img width="1000" height="1000" alt="image" src="https://github.com/user-attachments/assets/47bb538f-4935-43ea-90db-34b592aa51dc" />
<img width="1000" height="1000" alt="image" src="https://github.com/user-attachments/assets/a9cc701a-9db8-40db-b85c-a1acb4fdeda6" />
<img width="1000" height="1000" alt="image" src="https://github.com/user-attachments/assets/fdd5add8-e5d4-4060-b013-021f1ee280eb" />







📝 Future Improvements

✅ Email/SMS notification integration for request alerts

🌐 Google Maps API integration for geolocation-based donor matching

🧾 Donation history per user

🔄 Admin approval for new donor registrations

🔒 OTP-based authentication for donor login




👨‍💻 Tech Stack
Frontend: HTML5, CSS3, Bootstrap, JavaScript, jQuery

Backend: PHP 

Database: MySQL

Server: Apache (XAMPP)
