# Alumni Management System

The Alumni Management System is a web-based platform developed using PHP, JavaScript, HTML5, CSS, and MySQL. It aims to provide an efficient way for educational institutions to maintain a database of their alumni. This real-time, field-based project facilitates communication, networking, and engagement between the institution and its alumni community.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Features

- **User Authentication:** Secure login and registration for both alumni and administrators.
- **Alumni Profiles:** Alumni can create and update their profiles, including personal and professional information.
- **Event Management:** Administrators can create, edit, and delete events, allowing alumni to view and participate in various events.
- **Job Postings:** Alumni and administrators can post job opportunities, allowing alumni to explore and apply for them.
- **Admin Dashboard:** Admins have access to a dashboard for managing users, events, and other site content.
- **Alumni Directory:** A comprehensive directory of all registered alumni with the ability to connect and network.
- **Responsive Design:** The system is built using HTML5 and CSS to ensure a responsive user interface on various devices.

## Tech Stack

- **Frontend:** HTML5, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Tools:** XAMPP/WAMP/MAMP for local development

## Installation and Setup

### Prerequisites

- PHP (v7.4 or higher)
- MySQL Database
- Web Server (e.g., Apache)
- XAMPP/WAMP/MAMP for local development

### Steps to Install

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/alumni-management-system.git
    ```

2. **Move the Project to the Web Server:**

    Move the cloned project folder to the `htdocs` directory (for XAMPP) or the appropriate web server directory.

3. **Create the Database:**

    - Open phpMyAdmin (http://localhost/phpmyadmin).
    - Create a new database (e.g., `alumni_management`).
    - Import the SQL file located in the `database` folder of the project:
        - Go to the Import tab and upload the `alumni_management.sql` file.

4. **Configure Database Connection:**

    In the project folder, navigate to the `config` directory and open `db_config.php`. Update the database configuration with your MySQL credentials:
    ```php
    <?php
    $host = 'localhost';
    $username = 'root';
    $password = ''; // Your MySQL password
    $database = 'alumni_management';
    ?>
    ```

5. **Run the Project:**

    - Start Apache and MySQL from the XAMPP control panel.
    - Open a browser and go to [http://localhost/alumni-management-system](http://localhost/alumni-management-system).

## Usage

### For Alumni

- **Registration:** Sign up with your personal and professional details.
- **Profile Management:** Update and manage your profile.
- **Explore:** View and participate in events, job postings, and connect with fellow alumni.
- **Messaging:** Communicate with the institution and other alumni through private messages.

### For Admin

- **Dashboard Access:** Log in to the admin dashboard.
- **User Management:** Add, edit, and delete alumni profiles.
- **Event Management:** Create and manage events.
- **Job Postings:** Post job opportunities for alumni.
- **Notifications:** Send notifications to alumni regarding updates and events.

## Screenshots

(Include relevant screenshots of the application here)

## Contributing

If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- XAMPP for providing the local development environment.
- Bootstrap for UI components.
- Open-source libraries and tools used in this project.

## Contact

For any queries or feedback, please contact:

- **Name:** Murali
- **Email:** [muralisudireddy0@gmail.com](mailto:muralisudireddy0@gmail.com)
- **GitHub:** [MuraliChowdhary](https://github.com/Muralichowdhary)
